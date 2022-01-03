# MATH 462: Mathematics for Machine Learning
- Instructor: Adam Oberman
- Fall 2021

A mathematically rigorous approach to machine learning.

## Audience
Math and Stats Majors/Honours students, CS students.

## Prerequisites
- Math 223/Math 248 or equivalent (linear algebra majors/honours)
- Math 222 (Calculus 3)
- Math 324/Math 357 (Statistics)
- Probability course (implied, since it is a prerequisite for 324/357)
- Math 358 Honours Vector Calculus/Math 314 Advanced Calculus

## Related Courses

- Math 562, Winter 2022
  - This is a sequel to Math 462.  There will be a small amount of repetition of topics, since some students will not have taken 462.  However, to avoid repeated material, students from 462 will work on their project and be excused from HW problems which overlap.
- COMP 551 Applied Machine Learning https://www.siamak.page/courses/COMP551F21/index.html
  - This course focuses on implementation, rather than theory.  This a complementary course.
- COMP 451 Fundamentals of Machine Learning  https://cs.mcgill.ca/~wlh/comp451/
  - CS theory course, not currently offered.  Math 452 and Comp 451 are mutually exclusive.
- Math 308 Fundamentals of Statistical Learning
  - not offered this year.

## Textbook/References

-   [Mathematics for Machine Learning by Diesenroth](https://mml-book.github.io/) This book is elementary, but can be used as a reference or review of topics from the prerequisites
-   [Probabilistic Machine Learning: An Introduction by Kevin Patrick Murphy](https://probml.github.io/pml-book/book1.html) This book is encyclopedic, covers many topics, good reference, but not presented as digestible lectures
-   [Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/) by Shalev-Shwartz and Ben David  This book is very good for presenting machine learning problems, but less detailed on the proofs and part 3.
-   [Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/) by Mohri, Rostamizadeh, Talwalkar. This book contains rigorous proofs of generalization bounds, but assumes the reader is already familiar with the problems.
-   [High dimensional statistics, a non-asymptotic viewpoint](https://people.eecs.berkeley.edu/~wainwrig/) by Martin J Wainwright.

## Grading
- 5 HW assignments : 25%
- Group Project and Presentation: 15%
- Attendance 5%, Participation 5%.
- 2 Midterm Exams : 20%
- Final exam : 30%
- *Soft grading policy:* you are encouraged to make your best effort to complete all the work.  However, if you need to miss anything (assignment or exam), I will institute a soft grading policy which will allow one missed assignment and one missed midterm exam, with a small penalty.  Your final grade will be given by your average on the other work, with a penalty of:
  -   1% (for each assignment missed),
  -   2% (for a missed midterm).   
  -   3% (for a missed final exam)

E.g. if you missed one assignment and one midterm, with an average of 87% on the rest, then the penalty would be 87-(1+2) = 84%.  

## Key Dates
Refer to [McGill key Dates](https://www.mcgill.ca/importantdates/key-dates#Fall_2021)
- Classes begin: Weds Sept 1.
- Fall reading break: Tues-Weds Oct. 12-13
- Makeup day: Oct 15, no class.  
- Last class: Friday Dec 3rd.
- Midterm dates: TBD


# Lecture Notes :  MATH 462, Fall 2021

## Course Notes (typeset)
- [Course notes Part 1 (intro ML)](Math462_Lecture_Notes_Part_1.pdf)
- [UCourse note Part 2 (regression and binary classification)](https://www.overleaf.com/read/yzqkgwpswjkd)
- [Course notes part 3 (convex analysis and optimization)](https://www.overleaf.com/read/syvzdvznfmby)
- [Course notes part 4 (multiclass)](https://www.overleaf.com/read/qxxdjcdzccjy)
- [Course Notes (RL) HW version](https://www.overleaf.com/read/rtvnmmcjkgmn)

### Homework
- Homework 1 due noon, Monday Sept 20th [Homework 1 Revised](Math462_HW1_V4.pdf) and [Homework 1 Solution](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/MATH462.HW1.Soln.pdf)
- Homework 2, due 5pm, Tuesday Oct 5th, [Homework 2](Math462_HW2.pdf), and [HW 2 Solution](HW2.Soln.pdf)
- Homework 3, due 5pm, Tuesday Oct 19th, [Homework 3](https://www.overleaf.com/read/pmbgwhxztmxt) and [HW 3 Solution](HW3.Soln.pdf)
- Homework 4, due 5pm, Tuesday Nov 16th, [HW_4.pdf](HW_4.pdf)
- Homework 5, due 5pm, Monday Dec 6th (It's short!) [HW_5](https://www.overleaf.com/read/frrtfqpscwpk)

## Lectures Part 4 Reinforcement Learning
- Reference [Sutton Barto texbook](http://incompleteideas.net/book/the-book-2nd.html).  Refer to Part I: tabular RL (selected).  Part II, 9.1 and Ch 13 policy gradient method.  Ch 16 Case studies. 
- [Lecture 18](https://github.com/adam-oberman/adam-oberman.github.io/files/7530366/10.11.2021.Lecture18.pdf)
- [Lecture 19](https://github.com/adam-oberman/adam-oberman.github.io/files/7530369/12.11.2021.Lecture19.pdf)
- Lecture 20 - no notes, group work on projects. 
- Lecture 21 [19.11.2021.Lecture21.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/7591169/19.11.2021.Lecture21.pdf)

### Project
- [Project description](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Math%20462%20Project%20description.pdf)
- [Project Template 1](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Project%20Example%201.pdf)  
- [Project Template 2](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Project%20template%20Image%20Segmentation.md) 
- [Project Template 3](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Project%20Template%203%20Contrastive%20losses.md) 

## Lectures Part 3
### Weeks 8 and 9, Oct 27 and 29th, Nov 3rd and 5th
- (Weds) Project Outline and Examples (see links above)
- (Friday) [Lecture 15](29.10.2021.Lecture15.pdf) Deep Neural networks.
- Additional reference for CNNs: https://www.deeplearningbook.org/ Chapter 6 and Chapter 9
- (Weds) Face Verification Problem.  Generalization: in distribution and out of distribution [Lecture 16](03.11.2021.Lecture16.pdf) 
- (Friday) Unsupervised: cluster energy.  Semi-supervised SVM and margin.  Reinformence learning warmup. [Lecture 17](05.11.2021.Lecture17.pdf) 
### Week 7, Lectures
- Reference: Shalev-Shwartz Ch 17, Mohri Ch 9
- [Lecture 13](20.10.2021.Lecture13.pdf)
- [Lecture 14](22.10.2021.Lecture14.pdf)
### Week 5, Lecture 9 and 10, Week 6, Lecture 11 and 12
- Reference: Understanding Maching Learning, Shalev-Shwartz and Ben David, Chapters 12 and 14.
- Reference: [Boyd Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/), Chapters 2 and 3 and 9
- Class notes: [Lecture 9](09.29.Math462.L9.pdf) [Lecture 11](10.06.Math462.Lecture11.pdf) [Lecture 12](10.08.Lecture12.pdf)

## Lectures Part 2
### Week 3, Lecture 6, Sept 17 (F)
- Loss design for classification: zero-one loss and hinge loss.
### Week 4, Lecture 7, Sept 22 (W) and  Week 4, Lecture 8, Sept 24 (F)
- Read the notes [Working version of course notes Part 2](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Math462_Lecture_Notes_Part2.pdf) and discuss in class. 

## Lectures Part 1
### Week 1, lecture 1, Sept 1 (W)
- Introduction: example problems and datasets, meet and greet
- Reference: Murphy Ch1
### Week 1, Lecture 2, Sept 3 (F)
- Set up the supervised learning problem for regression
### Week 2, Lecture 3, Sept 8 (W)
- Regression, other losses, compare losses
- Calculus to find the minimizer of the (ELM) problem
- Reference: Course notes
### Week 2, Lecture 4, Sept 10 (F)
- Review of calculus and vector calculus, chain rule, gradient
- Compute gradient of the (EL) expected loss function
- Quadratic regression case
- References: Course Notes, Section "Gradients and Minimizers"
### Week 3, Lecture 5, Sept 15 (W)
- Instead of a lecture we will have a problem session, to work on HW1
### 
- [Old version of notes](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Math462_Lecture_Notes_Part_1.pdf) and [Old version of notes Letter format](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Math462_Lecture_Notes_Part_1_Letter.pdf)

## Earlier handwritten in class notes 
- [Lecture 1](09%2001%20Lecture%201.pdf)
- [Lecture 2](09%2003%20Lecture%202.pdf)
- [Lecture 3](09%2008%20Lecture%203.pdf)
- [Lecture 4](09%2010%20Lecture%204.pdf)
- [Tutorial 1](Tutorial%201_%20Linear%20Regression%20And%20Matrices.pdf)
- [Lecture 5](09%2015%20Math%20462%20Lecture%205.pdf)
- [Lecture 6](09.17.Math462.Lecture6%20.pdf)
- [Lecture 7](09.17.Math462.Lecture6%20.pdf)
- [Lecture 8](https://github.com/adam-oberman/adam-oberman.github.io/blob/main/Lectures/Math462.09.24.F.L8.pdf)

## Zoom recordings
- (No recording for lectures 1 and 2)
- [Lecture 3](https://mcgill.zoom.us/rec/share/VKdYKjgxXbdlP9_8l3xcSKz7E2A7Z_gwyOpYjbO1n9XQ-gSIO51ITa9Ug83cjejV.ZFHqMEOCdcJpXMx0?startTime=1631109875000)
- Lecture 4 and future lectures are only available in mycourses (due to McGill zoom recording policy). 

