## MATH 462, Fall 2022
### Honours Mathematics for Machine Learning,

Professor: Adam Oberman

Class: Monday, Wednesday, 10:05 am-11:25 am BURN 1214

Office Hours: BURN 1106, MW 11:30-12:00, and by appointment. Additional office hours TBA.

#### Audience: 

Math and Stats Majors/Honours students, Computer Science students.

#### Course Description:

A mathematically rigorous approach to Machine Learning (ML).  This course will cover the mathematical models which go into current machine learning models, as well as deep learning architectures, and application areas.  It will provide the necessary background for   understanding deep learning models and reading contemporary research papers. The sequel, Math 562, will go more deeply into mathematical aspects, such as statistical learning theory, and regularization.   

#### Course Webpages

- Course material:  https://adam-oberman.github.io/  
- Assigment submission: https://mycourses2.mcgill.ca/ 
- [Math 462 Fall 2022 First Day Handout.pdf](https://adam-oberman.github.io/pdfs/Math462/Math.462.Fall.2022.First.Day.Handout.pdf)

#### Lectures
08/31 (Weds): Discuss course, AI vs ML, Clustering intro
  - [Math 462 Fall 2022 First Day Handout.pdf](https://adam-oberman.github.io/pdfs/Math462/Math.462.Fall.2022.First.Day.Handout.pdf)
  - [RN AI book Ch1 excerpt](https://adam-oberman.github.io/pdfs/Math462/RN.AI.book.Ch1.excerpt.pdf)
  - [SS Ch 22 Clustering](https://adam-oberman.github.io/pdfs/Math462/SS.Ch.22.pdf)
 
09/07 (Weds): k-means clustering, losses, hypothesis classes

- [Math462_Lecture_Notes_Kmeans.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_Lecture_Notes_Kmeans.pdf)  (updated Sept 26)


09/12 (Monday): Vector Calculus Review, Vector Calc for ML: sigmoids.
09/14 (Wednesday): Vector Calc for ML. Generative and discriminative models.
- Reference: chapter 5 [MML Diesenroth](https://mml-book.github.io/) [MML] 
- [Math462_Lecture_Note_2_Calculus.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_Lecture_Note_2_Calculus.pdf)

Homework 1, posted Sept 20, due Sept 27 (in myCourses)  (updated Sept 27)
- [Math462_HW1.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_HW1.pdf)

09/14 (Monday) and 09/21 (Weds)
- no lectures, due to illness

09/26 (Monday)
- MML 3.1-3.6 Analytic Geometry (orthogonality)
- MML 10.1 Covariance Matrix 
- [Math462_Lect_InnerProd_PCA_1.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_Lect_InnerProd_PCA_1.pdf)

09/28 (Wednesday): Programming languages for the class, using Python and Collab.  K-means code.
- [Intro to Python Colab](https://colab.research.google.com/drive/1i5JbthN7UX8N14IjYBMdBiPW5M44cQUt?usp=sharing)
- [Intro to Numpy Colab](https://colab.research.google.com/drive/17kradohn-30zmf_VvWHv2g0QguXeenIj?usp=sharing)
- [K-means Colab](https://colab.research.google.com/drive/1w_uBtxKdBcAIZN51qxtIh99mnUJ1SNiI)

Homework 2, revised Oct 7
- [Math462_HW2.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_HW2.pdf)

10/03 (Monday) 
- no lectures, due to provincial election

10/05 (Wednesday)
- Review 3.8 of MM
- PCA Summary, [Math462_Lect_InnerProd_PCA_2.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_Lect_InnerProd_PCA_2.pdf)
- [PCA Colab](https://colab.research.google.com/drive/1MjaWPqB9-sQSI9r_Egj9Cu1AhBX276eU?usp=sharing)

10/13 (Thursday) first lecture after reading break
- Ch 19 of RN
- bias variance trade-off, etc
- toy example: Decision Trees [Decision Trees](https://adam-oberman.github.io/pdfs/Math462/RN_Decision_trees.pdf)

10/17 (Monday)
- Gain-loss equivalence (see other notes and HW)

10/19 (Wednesday)
- Section 19.5 PAC Learning Theory.
- Proof of Sample complexity bounds for finite hypotheses (19.1)

Homework 3, final version posted.
- [PCA Colab](https://colab.research.google.com/drive/1MjaWPqB9-sQSI9r_Egj9Cu1AhBX276eU?usp=sharing)
- [Math462_HW3.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_HW3.pdf)

10/24 (Monday), 10/26 (no lecture), 10/31 (Monday)
- Features
- Binary Classification 
- [Math462_Binary_Classification.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_Binary_Classification.pdf)

11/2 (Weds)
- [Math462_Binary_ClassificationII.pdf](https://adam-oberman.github.io/pdfs/Math462/Math462_Binary_ClassificationII.pdf)

11/7 (Monday): Features (handwritten notes)

11/9 (Weds): midterm

11/14 (Monday)
- gradient descent and SGD part 2. [Math462_Lecture_Note_SGD.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10058321/Math462_Lecture_Note_SGD.pdf)


11/16 (Weds) 
- RKHS Ch 12 of M. J. Wainwright (2019) High-dimensional statistics: A non-asymptotic viewpoint. [RKHS Ch 12 of M. J. Wainwright (2019) High-dimensional statistics: A non-asymptotic viewpoint.](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/7592A2B68EBB6F57B0AD042F8E812BEB/9781108498029c12_383-415.pdf/reproducing_kernel_hilbert_spaces.pdf)

- We covered 12.1 Hilbert Space Basics, and 12.2.1 PSD kernel functions

11/21 (Monday)
- RKHS Wainwright, Section 12.2.1, 12.2.2, 12.2.3

11/23 (Wednesday)
- RKHS.  Function norm in H 12.2.3.  Interpretation of K as similarity.  Kernel Ridge Regression (Section 12.5).

HW 4 Posted
- [HW4.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10126833/HW4.pdf)

- [Classification Code](https://colab.research.google.com/drive/1i9ep4yBvjAZwFOcO337w7weKhTlhfBQ6?usp=sharing)
- [GD and SGD Code](https://colab.research.google.com/drive/1-YoLDf3OyH3SxLJtC5W4qG3L1zYxkyMf?usp=sharing)

11/28 (Monday)
- RKHS: Cauchy-Schwatz inequality, proof that convergence in RKHS implies pointwise convergence.

HW 5 [HW5.pdf](https://github.com/adam-oberman/adam-oberman.github.io/files/10116658/HW5.pdf)

