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
Be sure to discuss both an early reference, and track back references to early work, which may be more clear. 
- Instructions [MathComp 562 Project Description.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10354909/MathComp.562.Project.Description.pdf)
- Suggested topics (2022) [Suggested Paper Links.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10354935/Suggested.Paper.Links.pdf)
- Suggested topics (2023)  [Project paper suggestions](https://docs.google.com/document/d/1XPO8v3ga8k2vnZqzIKlj-FrhLI0v94aCgy0d-xTO62o/edit?usp=sharing)

### Lectures and Homework

 - 01/05/2023 Zoom lecture, covered first day handout and projects.  Overview of Ch 2 of Bach: understanding "all you need is scale" vs. No Free Lunch Theorem.
 - 01/10/2023 In class.  Ch 2 Bach [Lecture 1 2023.01.10 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10386101/Lecture.1.2023.01.10.562.pdf)
 - 01/12/2023 Thursday.  Cheat Sheet for Measure Theory/Probability/ML Notation.  PAC Learning, reference: Mohri Ch2, SS 2.3.1 & Ch 3.  [Lecture 3 2022.01.12.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10438119/Lecture.3.2022.01.12.pdf)
 - 01/17/2023 Tuesday. 
 - 01/19 Thursday.  Reference:  Excerpt from [Jeff Calder](https://www-users.cse.umn.edu/~jwcalder/) notes on Calculus of Variations 
   - Random Variables, Markov, Chebyshev inequality [Calder Probability.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10451272/Calder.Probability.pdf)
   - Proof of concentration of measure results. Hoeffding Ineq. [Calder Concentration of measure.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10461076/Calder.Concentration.of.measure.pdf)
   - [Math562_HW_1.pdf (Jan 26, with code link)](https://github.com/adam-oberman/adam-oberman.github.io/files/10512477/Math562_HW_1.pdf)
   - [Math562_HW_1.pdf Jan 31](https://github.com/adam-oberman/adam-oberman.github.io/files/10551015/Math562_HW_1.pdf)

  - 01/24 and 26/2023  Rademacher Complexity. Reference: Chapter 3 of [Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/) by Mohri, Rostamizadeh, Talwalkar. 
  - Reference [Ch 14 Michael Mitzenmacher, Eli Upfa CH 14 Probability and Computing_ Randomization and Probabilistic Techniques in Algorithms and Data Analysis-C.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10689564/Ch.14.Michael.Mitzenmacher.Eli.Upfa.CH.14.Probability.and.Computing_.Randomization.and.Probabilistic.Techniques.in.Algorithms.and.Data.Analysis-C.pdf)

 - 02/7/2023 and 02/09/2023: 
 - Convex Learning Problems, Ch 12, S-S
 - Stability theory and generalization Ch 12, S-S
 - 02/14 and 16: Stability, SS Thm 13.2, Mohri Thm 14.2
 - 02/21 and 23: 
   - Convex upper bounds.  Classification: binary and multiclass losses.  Margin Loss.  Log Loss. 
   - Random Variables.  Feature Maps. 
 - [Math562_HW_2.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10748075/Math562_HW_2.pdf)

### Generative Model Lectures.
Reference  https://udlbook.github.io/udlbook/, Chapters 14-18
- 2023/03/07 and 09 Lecture Ch 14 and 15 
- [Notes on Unsupervised learning Generative Models.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10934574/Unsupervised.learning.Generative.Models.pdf)
- [Notes on GANS.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10934965/Ch.15.GANS.pdf)
- [Textbook Chapter Ch 16 Normalizing flows.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10993680/Ch.16.Normalizing.flows.pdf)
- [Textbook Chapter Ch 18 Diffusion.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10993678/Ch.18.Diffusion.pdf)

### Homework 3
- [Math562_HW_3.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/11034829/Math562_HW_3.pdf)

### Reinforcement Learning Lecture March 21 (handwritten notes and references below)
- References Learning Backgammon: 
  - [Temporal Difference Learning and TD-Gammon  Tesauro](https://bkgm.com/articles/tesauro/tdl.html)
  - Reference https://en.wikipedia.org/wiki/TD-Gammon 
  - https://usbgf.org/backgammon-basics-how-to-play/
- Bellman Equation  
  - https://en.wikipedia.org/wiki/Bellman_equation
- RL algorithms neural networks  
  - https://medium.com/ai%C2%B3-theory-practice-business/reinforcement-learning-part-1-a-brief-introduction-a53a849771cf
### Lecture March 23 (Thursday) Markov Decision Process
[Making Complex Decisions.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/11054397/Making.Complex.Decisions.pdf)
### Lecture March 28 (Tuesday) and March 30 (Thursday) Markov Decision Process II
- [Making Complex Decisions 2.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/11092887/Making.Complex.Decisions.2.pdf)
- Example calculation of the policy on a linear graph (determinstic and stochastic versions)
### Lecture April 4 (Tuesday) and April 6 (Thursday)  Contractions for Bellman Equation and error estimates
[MC_562_MDP.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/11174223/MC_562_MDP.pdf)

## Homework 4 (on generative models) (code link added)
- [Math562_HW_4_v4.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/11185967/Math562_HW_4_v4.pdf)

## Homework 5 (on RL and final lectures)
- will be a shorter HW, not to be turned in, but as practice for the final


## Final Exam
- will be based on the HW problems from mainly HW 1-4 with a bit from HW 5. (So related proofs, but nothing which was not covered in some way on the HW). 
- no need to study material from Generative Models/RL outside of the material on the HW




