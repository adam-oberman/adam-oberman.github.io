# MATH/COMP 562: Theory of Machine Learning, Winter 2023
### Honours Mathematics for Machine Learning

Professor: Adam Oberman https://www.adamoberman.net/

Teaching Assistant: Viet Nguyen baviet.nguyen@mail.mcgill.ca

Class time: Tuesday and Thursday 2:35pm - 3:55 pm.  [Lea 14](https://maps.mcgill.ca/?cmp=1&txt=EN&id=Leacock)

Office Hours: Tuesday and Thursday 1:05pm-1:30pm and 4:05pm-4:30pm. Wednesday 3:30-4:00pm (by appointment).  Occasionally family life interferes with my schedule, and I may miss the office hour.  An email in advance is appreciated, but is not necessary. 

Lecture notes and assignments:  https://adam-oberman.github.io/  

Assigment submission: https://mycourses2.mcgill.ca/ 

----
[First Day Handout 2023 MATHCOMP 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10360709/First.Day.Handout.2023.MATHCOMP.562.pdf)


##### Course Description

A mathematically rigorous approach to Machine Learning (ML), with a focus on a rigourous presentation of ML models.  Proofs of in-distribution generalization bounds.  

##### Audience 

- Math and Stats and theory oriented Computer Science graduate students.  
- Advanced undergraduate students who have prior background in implementing Machine Learning methods, and who plan to go on to graduate school. 

Students will be expected to have seen and coded ML models before. Experience with mathematical proofs and with probability is expected. 

### **Textbook**:

Learning Theory from First Principles, (January 1, 2023 edition)  [Free PDF](https://www.di.ens.fr/%7Efbach/ltfp_book.pdf),  by [Francis Bach](https://www.di.ens.fr/~fbach/)

#### Additional references

- [Mathematics for Machine Learning by Diesenroth](https://mml-book.github.io/) Review of prerequisites, with a ML focus.
- [Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/) by Shalev-Shwartz and Ben David  
- [Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/) by Mohri, Rostamizadeh, Talwalkar. 

Use Shalev-Shwartz for introduction and definitions.  Use Mohri for the proofs, which are more precise. 

- [High dimensional statistics, a non-asymptotic viewpoint](https://people.eecs.berkeley.edu/~wainwrig/) by Martin J Wainwright. Advanced book on concentation of measure topics in machine learning.  The first chapters are a good source of advanced material on concentration of measure.  However, this material is covered in Bach Ch 1.  

### Project

Instructions [MathComp 562 Project Description.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10354909/MathComp.562.Project.Description.pdf)
Suggested topics (old version) [Suggested Paper Links.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10354935/Suggested.Paper.Links.pdf)

### Lectures and Homework

 - 01/05/2023 Zoom lecture, covered first day handout and projects.  Overview of Ch 2 of Bach: understanding "all you need is scale" vs. No Free Lunch Theorem.
 - 01/10/2023 In class.  Ch 2 Bach [Lecture 1 2023.01.10 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10386101/Lecture.1.2023.01.10.562.pdf)
 - 01/12/2023 Thursday.  Cheat Sheet for Measure Theory/Probability/ML Notation.  PAC Learning, reference: Mohri Ch2, SS 2.3.1 & Ch 3.  [Lecture 3 2022.01.12.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10438119/Lecture.3.2022.01.12.pdf)
 - 01/17/2023 Tuesday. 
 - 01/19 Thursday.  Reference:  Excerpt from [Jeff Calder](https://www-users.cse.umn.edu/~jwcalder/) notes on Calculus of Variations 
   - Random Variables, Markov, Chebyshev inequality [Calder Probability.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10451272/Calder.Probability.pdf)
   - Proof of concentration of measure results. Hoeffding Ineq. [Calder Concentration of measure.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10461076/Calder.Concentration.of.measure.pdf)
   - [Math562_HW_1.pdf (Jan 26, with code link)](https://github.com/adam-oberman/adam-oberman.github.io/files/10512477/Math562_HW_1.pdf)
   - [Math562_HW_1.pdf Jan 31 tiny edit](https://github.com/adam-oberman/adam-oberman.github.io/files/10548658/Math562_HW_1.pdf)


  - 01/24 and 26/2023  Rademacher Complexity. Reference: Chapter 3 of [Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/) by Mohri, Rostamizadeh, Talwalkar. 

Future Lectures:  
 - High Dimensional Probability  


### Project paper suggestions
Be sure to discuss both an early reference, and track back references to early work, which may be more clear.
#### Suggested project papers (Early references)
- [John N Tsitsiklis and Benjamin Van Roy. Optimal stopping of markov processes: Hilbert space theory, approximation algorithms, and an application to pricing high-dimensional financial derivatives. .pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10513421/John.N.Tsitsiklis.and.Benjamin.Van.Roy.Optimal.stopping.of.markov.processes.Hilbert.space.theory.approximation.algorithms.and.an.application.to.pricing.high-dimensional.financial.derivatives.pdf)

- [Learning theory: stability is sufficient for generalization and necessary and sufficient for consistency of empirical risk minimization](https://link.springer.com/article/10.1007/s10444-004-7634-z)
-  [Learning with differential privacy: Stability, learnability and the sufficiency and necessity of ERM principle](https://www.jmlr.org/papers/volume17/15-313/15-313.pdf)
- [Robustness and generalization](https://link.springer.com/article/10.1007/s10994-011-5268-1)
- [Representation learning: A review and new perspectives](https://ieeexplore.ieee.org/abstract/document/6472238/)
- [Rich Feature Hierarchies for Accurate Object Detection and Semantic Segmentation](https://openaccess.thecvf.com/content_cvpr_2014/html/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.html)  (What do they say about features?)
- [A survey on deep learning in medical image analysis](https://www.sciencedirect.com/science/article/pii/S1361841517301135)
- [Learning Transferable Features with Deep Adaptation Networks](https://proceedings.mlr.press/v37/long15)
 
#### Suggested project papers (highly cited recent papers)
- [Steps Toward Deep Kernel Methods from Infinite Neural Networks](https://arxiv.org/abs/1508.05133)
- [Deep neural networks as gaussian processes](https://arxiv.org/abs/1711.00165)
- [Neural tangent kernel: Convergence and generalization in neural networks](https://proceedings.neurips.cc/paper/2018/file/5a4be1fa34e62bb8a6ec6b91d2462f5a-Paper.pdf)
-[Physics-informed machine learning](https://www.nature.com/articles/s42254-021-00314-5)
- [Train faster, generalize better: Stability of stochastic gradient descent](http://proceedings.mlr.press/v48/hardt16.html)
