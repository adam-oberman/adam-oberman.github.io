### Project example 2: Image Segmentation

Survey: https://arxiv.org/abs/2001.05566, 22 pages.

Loss?  Accuracy?  Different ways to count errors (on a per-pixel basis).

https://en.wikipedia.org/wiki/Jaccard_index

https://en.wikipedia.org/wiki/S%C3%B8rensen%E2%80%93Dice_coefficient

https://medium.com/@ihor.shylo/improving-performance-of-image-segmentation-with-conditional-random-fields-crf-8b93f7db396c



Better: https://nanonets.com/blog/semantic-image-segmentation-2020/ 

Section Metrics and Section losses.

post-processing step to improve the boundary:

<img src="/Users/aoberman/Dropbox/2021 Fall Math 462/Math 462 Lectures/Math 462 Project/project example 2 Image segmentation/Project example 2.assets/0-E9W6TOPsHrERQqvH.png" alt="0-E9W6TOPsHrERQqvH" style="zoom:25%;" />

<img src="/Users/aoberman/Dropbox/2021 Fall Math 462/Math 462 Lectures/Math 462 Project/project example 2 Image segmentation/Project example 2.assets/0-PBQ2nSCtVFJ5miJZ.png" alt="0-PBQ2nSCtVFJ5miJZ" style="zoom:25%;" />





#### Step 1. Can  Define the "metric for errors".  I.e. define the loss!

Define a loss and compare losses.

#### Step 2: is there a surrogate loss, a differentiable loss which would be more amenable to training?

Can you define a differentiable surrogate loss?

**Step 3**: can you do postprocessing to remove "noise" in the pixels?  See https://www.numerical-tours.com/matlab/denoisingsimp_4_denoiseregul/ https://nanonets.com/blog/semantic-image-segmentation-2020/

#### **Improving output with CRF**

Pooling is an operation which helps in reducing the number of parameters in a  neural network but it also brings a property of invariance along with  it. Invariance is the quality of a neural network being unaffected by  slight translations in input. Due to this property obtained with pooling the segmentation output obtained by a neural network is coarse and the  *boundaries are not concretely defined.*

To deal with this the paper proposes use of graphical model CRF.  Conditional Random Field operates a post-processing step and *tries to  improve the results produced to define shaper boundaries. It works by  classifying a pixel based not only on it's label but also based on other pixel labels.* As can be seen from the above figure the coarse boundary  produced by the neural network gets more refined after passing through  CRF.

**This part is math: using neighborhoods and spatial gradients to improve the outputs.**



## **Loss functions**

Loss  function is used to guide the neural network towards optimization. Let's discuss a few popular loss functions for semantic segmentation task.

**Cross Entropy Loss**

Simple average of cross-entropy classification loss for every pixel in the  image can be used as an overall function. But this again suffers due to  class imbalance which FCN proposes to rectify using class weights

UNet tries to improve on this by giving more weight-age to the pixels near  the border which are part of the boundary as compared to inner pixels as this makes the network focus more on identifying borders and not give a coarse output.

**Focal Loss**

Focal loss was  designed to make the network focus on hard examples by giving more  weight-age and also to deal with extreme class imbalance observed in  single-stage object detectors. The same can be applied in semantic  segmentation tasks as well

**Dice Loss**

Dice  function is nothing but F1 score. This loss function directly tries to  optimize F1 score. Similarly direct IOU score can be used to run  optimization as well

**Tversky Loss**

It is a variant of Dice loss which gives different weightage to FN and FP

**Hausdorff distance**

It is a technique used to measure similarity between boundaries of ground  truth and predicted. It is calculated by finding out the max distance  from any point in one boundary to the closest point in the other.  Reducing directly the boundary loss function is a recent trend and has  been shown to give better results especially in use-cases like medical  image segmentation where identifying the exact boundary plays a key  role.

The advantage of using a boundary loss as compared to a  region based loss like IOU or Dice Loss is it is unaffected by class  imbalance since the entire region is not considered for optimization,  only the boundary is considered.

### Conclusion:

This is a great example of a problem where the engineering/architecture challenges were more important that problem loss design.

- i.e. better loss may not help if competitor has better model/training.

However, now, better loss and best models are possible.  So: can we do a math analysis of the loss, and prove that it does what we want?

Currently, no consensus on ways to best measure

- accuracy, i.e. 0-1 loss (because of class imbalances).  This related to FP/FN which we studed in class.  
  - Idea: Maybe we can use a differentiable loss which is sensitive to FP/FN, and to take into account the class imbalance?
- Surrogate loss. I.e. training loss, which is differentiable, upper bound to accuracy.

### Project:

- Can you read the papers and see if there is a precise way to intepret what they are (loosely) saying?
- Identify loose statements, and "bet/guess" if the lack of clarity is on the author or the reader side. (i.e. is it their mistake)
- Can you make a (possibly imperfect) but precise definition, and prove something about it.
- E.g. we want a perfect loss which measure total errors, but also doesn't flip classes when there is an imbalance.  This is not possible because ...  However, if we make the reasonable assumption that ... Then we can have a loss which, under these conditions, will do the job.  In the case where we expect ... then we should be aware that we would be better of doing ...  (With math justification)
- Whenever possible, go to the simplest possible case, of 2 classes, balanced.  Then 2 classes imbalanced, etc.

Advanced project:

- Can you look at existing metrics, and make a definition.  Compare the pros and cons for each choice, in terms of class imbalance?

- Can you define a surrogate loss which would be better for training?