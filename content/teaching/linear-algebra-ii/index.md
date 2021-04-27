+++
# Date this page was created.
date = "2021-04-01"

# Project title.
title = "Linear Algebra II"

selected = true
toc = true



# Project summary to display on homepage.
summary = "A 15 lecture course which introduces intermediate level topics in Linear Algebra."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
#tags = ["deep-learning"]
projects = ["maths", "theory-cs"]


page_type = "main"

# Optional external URL for project (replaces project detail page).
# external_link = "http://ml4science.iiit.ac.in/"

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

A 15 lecture course which introduces intermediate level topics in Linear Algebra. 

## Prerequisites
Assumes that Linear Algebra I is covered. Specifically assumes knowledge of the following topics:

- Solutions to Linear Equations, Echelon Forms, Gaussian Elimination
- Field, Vector Space Defintions, Real, Complex, Finite Field based Vector Spaces
- Linear Transformation, Matrix, Rank, Inverse, Transpose
- Change of Basis and effect on Matrix of the Linear Transformation
- Determinants

## Schedule

### Meetings

##### Live Lectures
From 30th March to 4th May, 2021, Tuesdays, Thursdays and Saturdays
- 10-11 AM for Batch 2
- 12-01  PM for Batch 1


##### Tutorials
Weekly tutorials conducted by TAs in smaller groups as per times fixed.


##### Office Hours
I will be available on Teams during the timings given bellow, for clearing any doubts. 
You can sent a direct message to me for joining.
- Monday, 530-730PM.
- Thursday, 330-530PM.

### Expected Workload
Students are expected to spent atleast 12 hrs per week. Roughly
- 3+1 hrs attending lectures and tutorials
- 4 hrs reading textbooks, references etc 
- 4 hrs solving assignments, quizes etc

### Evaluations
- 4 Light Quizzes (Weekly)
- 3 Assignments
- 2 Deep Quizzes (17th April, 4th May)

## Textbook and References

### Textbook
The resources provided are licenced under Creative Commons/Open Licences and hence downloadable.

- \[CDTW\] [Linear Algebra](https://www.math.ucdavis.edu/~linear/)  
  David Cherney, Tom Denton, Rohit Thomas and Andrew Waldron

- \[WKN\] [Linear Algebra with Applications](https://lyryx.com/linear-algebra-applications/)  
  W. Keith Nicholson

- \[MR\] [Interative Linear Algebra](https://textbooks.math.gatech.edu/ila/)  
  Dan Margalit and Joseph Rabinoff

- \[DA\] [Understanding Linear Algebra](http://merganser.math.gvsu.edu/david/linear.algebra/ula/ula/ula.html)  
  David Austin

### Extra Reading
- [Down with Determinants](https://www.maa.org/sites/default/files/pdf/awards/Axler-Ford-1996.pdf)  
  Sheldon Axler

- [Linear Algebra Done Right Videos](https://linear.axler.net/LADRvideos.html)  
  Sheldon Axler

- [Markov Chains and Google's PageRank Algorithm](http://merganser.math.gvsu.edu/david/linear.algebra/ula/ula/sec-stochastic.html)  
  Understanding Linear Algebra, David Austin.

- [The Fast Fourier Transform and Polynomial Multiplication](http://www.cs.ust.hk/mjg_lib/Classes/COMP3711H_Fall16/lectures/FFT_Slides.pdf)  
  Mordecai GOLIN

- \[GS\] [Linear Algebra MIT OCW Course Materials](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/resource-index/)   
  Gilbert Strang

### On Solving Problems & Understanding Proofs

- [Richard Feynman, His Life, and the Art of Solving Important Problems](https://www.jurnalanas.com/feynman-and-the-art-of-problem-solving/)  
  Blog Post

- [How to Solve it](https://math.hawaii.edu/home/pdf/putnam/PolyaHowToSolveIt.pdf)   
  G. Polya  
  [Shorter Version](https://math.berkeley.edu/~gmelvin/polya.pdf)


## Lecture Topics

### Eigenvalues & Diagonalization

#### 1. Linear Algebra & Random Walks  
   Recalling Basics | Function Spaces | Random Walk on Graphs 
   - [Notes](notes/lec1.pdf) | [Video](https://web.microsoftstream.com/video/7dfd9faa-f14f-4b7f-ad7c-43480bf9ecb3)
   - Reading
     - Section 2.9 in [WKN]

#### 2. Eigenvectors and Eigenvalues  
   Definitions | Characteristic Polynomial | Examples
   - [Notes](notes/lec2.pdf) | [Video](https://web.microsoftstream.com/video/4465dd79-af1d-4400-b575-e52c312fe944)
   - Reading  
      - Section 3.3 for Eigenvalues, Section 2.9 for Random Walks on Graphs in [WKN].
  	  - Chapter 12 in [CDTW].
    
#### 3. Diagonalization   
   Eigenvector Basis and Powering | Multiplicities  
   - [Notes](notes/lec3.pdf) | [Video](https://web.microsoftstream.com/video/a26c1382-d6ee-4668-a5e8-15add4db7987)
   - Reading
       - Section 3.3 in [WKN]  
  	   - Chapter 13 in [CDTW]

#### [Assignment 1](problems.pdf)
Submit by 13th April
   
### Norms & Inner Products

#### 4. Norms & Inner Products   
   Jordan Form | Norms | Distance | Inner Product | Complex Case  
   - [Notes](notes/lec4.pdf) | [Video](https://web.microsoftstream.com/video/b4452435-fa85-4d1c-92a1-6e5f28e36db2)  
   - Reading
       - Section 10.1 in [WKN]
   - Explore 
       - For Jordan Form, Generalized Eigenvectors, see [Down with Determinants](https://www.maa.org/sites/default/files/pdf/awards/Axler-Ford-1996.pdf).
       - [Geometric Multiplicity $\leq$ Algebraic Multiplicity.](http://www.ee.iitm.ac.in/~uday/2017b-EE5120/multiplicity.pdf) 
       - [Rotation Matrics have complex eigenvalues.](http://scipp.ucsc.edu/~haber/ph116A/Rotation2.pdf)
  
#### 5. Orthonormal Vectors 
   Orthogonal & Orthonormal Vectors | Gram-Schmidt Orthogonalization  
   - [Notes](notes/lec5.pdf) | [Video](https://web.microsoftstream.com/video/fdfb2b3e-dd75-444c-b69d-7e7ca4861924)  
   - Reading
       - Section 10.2 in [WKN]
       - Chapter 14 in [CDTW]
   - Explore 
       - For Bilinear forms see [Slides of Prof. P. Karageorgis](https://www.maths.tcd.ie/~pete/ma1212/chapter3.pdf).


#### 6. Projection and Orthogonal Complement
   Subspace Projections | Orthogonal Complements | Fitting with Errors
   - [Notes](notes/lec6.pdf) | [Video](https://web.microsoftstream.com/video/930ca162-6b12-4482-8c2d-24403355e4b0)
   - Reading
       - Section 14.6 in [CDTW]
       - Section 8.1 in [KTW]

### Advanced Topics

#### 7. Least Squares Fitting 
   Best fit vector on a subspace | Least Squares Fitting Equation
   - [Notes](notes/lec7.pdf) | [Video](https://web.microsoftstream.com/video/97dd19eb-b92d-4c00-ba9e-84e0dff7c2fb)
   - Reading
     - \[MR\] [Section 6.5](https://textbooks.math.gatech.edu/ila/least-squares.html)
     - Chapter 7 (upto page 307) in [CDTW]

#### 8. Deep Quiz I and Discussion
   - [Notes](notes/lec8.pdf) | [Video](https://web.microsoftstream.com/video/6adb50ee-9d24-430c-823d-3f2a6462c271)



#### [Assignment 2](problems.pdf)
Submit by 26th April

#### 9. Symmetric Matrices and Properties
  Eigenvalues and eigenvectors of Symmetric Matices | Spectral Theorem
   - [Notes](notes/lec9.pdf) | [Video](https://web.microsoftstream.com/video/7f995877-9281-42c2-83b4-2b40a3fc10bb)
   - Reading
     - Chapter 15 in [CDTW]  
   - Solve  
     - Question 3, 5 in Review Problems 15.1 in [CDTW]
     - If $P$ is the change of basis matrix for changing coordinates from standard basis to another orthonormal basis, then columns of $P$ are orthonormal.
     - If columns of $P$ are orthonormal then rows of $P$ are also orthonormal.


#### 10. Spectral Decomposition Theorem
  Spectral Theorem | Spectral Decomposition
   - [Notes](notes/lec10.pdf) | [Video](https://web.microsoftstream.com/video/829c0127-407e-4f78-b1ee-178ee1efae80)
   - Reading
     - Section 10.3 in [WKN]
     - Chapter 15 in [CDTW]
   - Solve
     - Let $v_1,\cdots, v_n$ be a basis for an $n$ dimensional vector space $V$ over some field $\mathbb F$ and let $M,M' \in \mathbb F^{n\times n}$ be matrices. Show that if $$\forall i \in \\{1,\ldots, n\\},\qquad Mv_i = M'v_i$$ then $M=M'$.  
     - Consider the $n$ dimenstional complex vector space $\mathbb C^n$. Is $\mathbb R^n$ a subpace of $\mathbb C^n$?  
     - We know that $\mathbb R^n$ is a subset of $\mathbb C^n$. Suppose $v_1,\ldots, v_n \in \mathbb R^n$ be orthonormal vectors. Can they form a basis for $\mathbb C^n$?

#### 11. Singular Value Decomposition
  Spectral Theorem for Complex Spaces | Singular Value Decomposition
   - [Notes](notes/lec11.pdf) | [Video](https://web.microsoftstream.com/video/b5980684-abdb-46f1-9354-fbf1fa60fa1a)
   - Reading
     - Section 17.2 in [CDTW]
     - Section 8.6 in [WKN]

### Applications

#### 12. PCA & Best Fit Subspaces
  Principal Component Analysis | Applications in Data Science
  - [Notes]() | [Video]() 
  - Reading
  - Code
    - [Finding axis of a spiral galaxy.](https://colab.research.google.com/drive/1DQBLsKjFSrxi5IBH8rFE42FjZVOo7Tgi?usp=sharing)
  - Explore
    - Chapter 3 in [Foundations of Data Science by Blum, Hopcroft, and Kannan](https://www.cs.cornell.edu/jeh/book.pdf).  
      Has proofs for SVD giving best fit subspaces.
    - [PCA and Image Compression](http://people.ciirc.cvut.cz/~hlavac/TeachPresEn/11ImageProc/15PCA.pdf). 

#### Assignment 3
Submit by 27nd April

#### 13. Sparse Recovery and Pooled Testing (Tentative)

   - Explore
     - [Compressive Sensing](https://web.stanford.edu/class/cs168/l/l17.pdf)  
       Lecture Notes. Tim Roughgarden & Gregory Valiant.

#### 14. Course Summary & Closing Notes.


#### 15. Deep Quiz II
On 4th May
