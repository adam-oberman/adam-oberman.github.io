# MATH/COMP 562: Theory of Machine Learning
### Winter 2021, Adam Oberman https://www.adamoberman.net/
### COVID
McGill has announced online teaching for this course, at least until January 24th.  I hope we can return to in person teaching, which will be better for group work and presentations. 
### Prerequisites
Prerequisites: MATH 462 or COMP 451 or (COMP 551, MATH 222, MATH 223 and MATH 324) or ECSE 551.
### Teaching Assistants
Viet Nguyen: baviet.nguyen@mail.mcgill.ca
Gabriela Moisescu-Pareja: gabriela.moisescu-pareja@mail.mcgill.ca

### Related Courses
- [Math 462, Fall 2021](https://github.com/adam-oberman/adam-oberman.github.io/tree/main/Lectures)
  - To make sure that we all have the same background, there will be some overlap with this course in the first few weeks of term (of the 80+ students in 562, under 20 took 452).   Students from 462 can start their projet, and be excused from the small number of HW problems which overlap.
- [COMP 551 Applied Machine Learning](https://www.siamak.page/courses/COMP551F21/index.html)
  - This course focuses on implementation, rather than theory.  This a complementary course.
### References
- [Notes from Math 462](https://github.com/adam-oberman/adam-oberman.github.io/tree/main/Lectures)
- NLP Book https://mitpress.mit.edu/books/introduction-natural-language-processing
- Deep Learning book  https://www.deeplearningbook.org/
- RL Book http://www.incompleteideas.net/book/the-book-2nd.html
#### Additional general references
- [Mathematics for Machine Learning by Diesenroth](https://mml-book.github.io/) Review of prerequisites, with a ML focus.
- [Probabilistic Machine Learning: An Introduction by Kevin Patrick Murphy](https://probml.github.io/pml-book/book1.html) Good reference for many topics, but not presented as digestible lectures
#### ML Theory references
- [Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/) by Shalev-Shwartz and Ben David  This book is very good for presenting machine learning problems.
- [Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/) by Mohri, Rostamizadeh, Talwalkar. Rigorous proofs of generalization bounds for classification problems.  VC dimension, Rademacher complexity. 
- [High dimensional statistics, a non-asymptotic viewpoint](https://people.eecs.berkeley.edu/~wainwrig/) by Martin J Wainwright. (First couple chapters only),  good math reference for concentration of measure which is used in the generalization bounds.  

### Grading 
Update (Jan 21). 
- Attendance and Participation  (attend group presentations, ask questions, screen on for zoom when possible): 10%
- Group Project.  Writeup and presentation:30% 
- Homework: 30%
- Individual Project/Final Report: 30%

*Changes due to COVID* I reserve the right to make changes to the assignment structure/grading scheme in response to the COVID situation.  However, significant changes will be presented to the class for feedback, and will go forward only if there is strong agreement by the class. 

### Key Times and Dates (TBD)
Refer to [McGill key Dates](https://www.mcgill.ca/importantdates/key-dates#Winter_2022)
- Classes are every Tuesday and Thursday 11:30-1pm.  
 - First class: Thursday Jan 6th. (11:30am-1pm, zoom link on mycourses page).   
 - Reading Break: Feb 28 - March 4th
- Classes end Tuesday April 12th. 

### Course Topics
- Prerequisite material (which will be covered in more detail later in the course) 
  - Foundational Machine Learning: Classification, binary and multi-classes.  Classification losses, convex surrogate losses.  
  - Scoring function and class probability interpretations.  
  - Training models: Optimization, stochastic gradient descent. 
  - Later in the course: Introduction to deep learning. Introduction and math background for computer vision/generative models, NLP, RL.
### Outline
- Part 1: Introduction to Machine Learning, Deep Learning.  Topics in deep learning: Reinforcement Learning, Natural Language Processing, Computer Vision.   Generalization in (shallow) machine learning.  References: Shalev-Shwartz (first part), Mohri (latter part).  PAC Learning bounds, VC dimension, Concentration of measure, Rademacher complexity.

### Homework
- [Math562_HW1_V2.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7945227/Math562_HW1_V2.pdf)

### Group and individual projects
- Stage 1,Tues Feb 1st (choose topics and groups).  See suggestions [Suggested Paper Links.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7951096/Suggested.Paper.Links.pdf)
- Stage 2 (outline and plan) Thurs Feb 3rd.  
- Stage 3: see instructions [MathComp 562 Project Description.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7943833/MathComp.562.Project.Description.pdf)

### Course Notes
Chapter References [Machine Learning]: 
- [SS] "[Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/)" by Shalev-Shwartz and Ben David.  
- [M] "Foundations of Machine Learning" Mohri, Rostamizadeh, Talwalkar. 
Chapter References [Reinforcement Learning]:
- "[Reinforcement Learning: Theory and Algorithms](https://rltheorybook.github.io)" by Alekh Agarwal, Nan Jiang, Sham M. Kakade, and Wen Sun.
- "[Algorithms for Reinforcement Learning](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)" by Csaba Szepesvari
#### Lecture 1: 
- Read [SS, Chapter 1] on your own.
- Types of Learning, [SS Section 1.3] : 
- Statistical Learning FrameworkEmpirical Risk Minimization
- Overfitting, [SS Section 2.1, 2.2]
- [Notes from Lecture 1](https://github.com/adam-oberman/adam-oberman.github.io/files/7824026/Lecture.1.2022.01.06.MC.562.pdf)  
#### Lecture 2: 
- Read [M, Ch 1] on your own. 
- Review linear predictors, linear classification, linear regression.  References: [SS Ch 9] or Math 462 course notes.
-  [Lecture 2 (class notes)](https://github.com/adam-oberman/adam-oberman.github.io/files/7863498/L2.2022.01.11.Lecture.2.pdf) Reference Mohri Ch 2. 
- PAC Learning Framework [M 2.1]
- Learning Guarantees: Finite hypothesis sets, consistent case. [M 2.2]
- Equivalent references: [SS 2.3 and SS 3.1]
#### Lecture 3
- [SS 4.2] Hoeffding's inequality
- [SS 5.2] Bias complexity trade-off.
- [Lecture 3.  2022.01.12 Math Comp 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7865071/Lecture.3.2022.01.12.Math.Comp.562.pdf)
#### Lectures 4
- Rademacher complexity.  [M 3.1]
- [Lecture 4.  2022.01.17 (Tuesday) MATHCOMP 562 combined.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7897621/Lecture.4.2022.01.17.Tuesday.MATHCOMP.562.combined.pdf)
#### Lecture 5
- Rademacher Complexity Proof [M 3.1], 
- [Lecture 5 2022.01.19 (Thursday) MATHCOMP 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7934527/Lecture.5.2022.01.19.Thursday.MATHCOMP.562.pdf)
#### Lecture 6
- Understanding Rademacher complexity
- Talagrand's Lemma
- [L6 2022.01.25 Lecture 6.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7945255/L6.2022.01.25.Lecture.6.pdf)
#### Lecture 7
- Rademacher complexity application to classification with linear Hypothesis [M 5.4][L7 2022.01.27 Thursday Lecture 7.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7953145/L7.2022.01.27.Thursday.Lecture.7.pdf)
#### Lecture 8
- Bayes classifier (Mohri 2.41, 2.4.2), 
- No free lunch Theorem [SS Section 5.1], 1. [SS 5.2]   See [Illustrated proof](https://mlu.red/muse/52449366310.html)
- Bias-variance error decomposition = [M 4.1]  
- Estimation-Approximation error decomposition.  Structural Risk minimization [M 4.3] 
- [Lecture 8.  2022.02.01 (Tuesday) MATHCOMP 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7982236/Lecture.8.2022.02.01.Tuesday.MATHCOMP.562.pdf)
#### Lecture 9
- proof of No Free Lunch Theorem
- VC dimension
- [Lecture 9.  2022.02.03 (Thursday) MATHCOMP 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7995200/Lecture.9.2022.02.03.Thursday.MATHCOMP.562.pdf)
#### Lecture 10 
- RKHS introduction.  Ref: Wainwright Ch 12 section 1 and 2, RKHS
- [Lecture 10.  2022.02.08 (Tuesday) MATHCOMP 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/8026550/Lecture.10.2022.02.08.Tuesday.MATHCOMP.562.pdf)
#### Lecture 11
- RKHS theory, Ref: Wainwright Ch 12 section 2 and 3, RKHS
- Guest lectures from former students on RL for ventilator and word embeddings.
#### Lecture 12
- RKHS applications: function fitting and density estimation, section 12.5 and 12.6
- Introduction to Reinforcement Learning: MDPs, Policy, Value function, the RL objective
#### Lecture 13
- Bellman expectation equations, Bellman optimality equations (and respective operators)
- Optimal value function if and only if satisfies the optimality equations
- Solving MDPs when dynamics are known: value iteration vs. policy iteration, sample efficiency
#### Lecture 14
- When dynamics and rewards are unknown: predicting the value function
- TD learning, convergence "proof", off-policy learning
- Q-learning algorithm: applying TD ideas to controlling the agent
#### Lecture 15
- Q-learning revisited
- Deep Q-learning (DQN): experience replay and stable TD targets
- Introduction to exploration in model-based learning for finite-horizon MDPs
#### Lecture 16 (prof. Panangaden)
- Bisimulation, bisimulation metrics for MDPs
- Metrics on the space of probability distributions, coupling, Kantorovich metric
- Frontiers
- [Notes](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/notes-prakash-bisims.pdf)

