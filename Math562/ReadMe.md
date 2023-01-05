# MATH/COMP 562: Theory of Machine Learning, Winter 2023
### Honours Mathematics for Machine Learning

Professor: Adam Oberman https://www.adamoberman.net/

Teaching Assistant: Viet Nguyen baviet.nguyen@mail.mcgill.ca

Class time: Tuesday and Thursday 2:35pm - 3:55 pm.  [Lea 14](https://maps.mcgill.ca/?cmp=1&txt=EN&id=Leacock)

Office Hours: TBD, and by appointment.

Lecture notes and assignments:  https://adam-oberman.github.io/  

Assigment submission: https://mycourses2.mcgill.ca/ 

----

[First Day Handout 2023 MATHCOMP 562.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10354898/First.Day.Handout.2023.MATHCOMP.562.pdf)

##### Course Description

A mathematically rigorous approach to Machine Learning (ML), with a focus on a rigourous presentation of ML models.  Proofs of in-distribution generalization bounds.  

- This course assumes familiarity with the ML models discussed, and experience implementing the models.  It provides a deeper theoretical analysis,
- There currently is no useful theory for deep learning methods, they are still primarily achieving success using engineering methods.  This course aims to cover theory topics from machine learning which experts believe will be relevent to the to-be-developed theory for deep learning.   

##### Audience 

- Math and Stats and theory oriented Computer Science graduate students.  
- Advanced undergraduate students who have prior background in implementing Machine Learning methods, and who plan to go on to graduate school. 

Students will be expected to have seen and coded ML models before. Experience with mathematical proofs and with probability is expected. 

### Grading 

- Final exam: 50% 
- HW assignments : 20% (5-7, approximately biweekly)
- Project: 20%
- Attendance 5%.  
- Participation : 5%. 

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

### Lecture Plan

(Schedule may be adjusted according to the class needs.  Lecture plan will be updated on the course page)

Introduction

- Introduction to supervised learning, Bach Ch2,  (3 lectures)
- Linear least-squares regression theory, Bach Ch 3, implementation,  (3 lectures) 

Generalization bounds for learning algorithms 

- Empirical Risk Minimization, 
  - Bach Ch 4, (3 lectures) 
  - Concentration of Measure, McDiarmid's inequality, Bach Ch1, (1 lecture)
- Stability approach, Shalev-Shwartz Ch 13,  Mohri Ch 14 (1 lecture)
  - See also Bach Ch 5 for definitions of convex, strongly convex, smooth functions
- Optimization for Machine Learning, Bach Ch 5, 3 lectures
- Local Averaging Methods, Bach Ch6, 2 lectures
- Kernel Methods, Bach Ch 7, 4 lectures
- Neural Networks, Bach Ch 9 and other references, 4 lectures
- Additional topics and final exam review, remaining (2-3) lectures. 

