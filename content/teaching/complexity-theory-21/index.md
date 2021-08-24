+++
# Date this page was created.
date = "2021-07-01"

# Project title.
title = "Complexity Theory I"

selected = true

# Project summary to display on homepage.
summary = "A short 12 lecture course on Computability and Complexity Theory."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
projects = ["complexity-theory", "theory-cs"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true
toc = true


page_type = "main"

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

First part of the course topics are here. 

Second part of the course invloving advanced topics like PSPACE, Space bounded computations, Polynomial Hierarchy, Arithmetic Circuits, Boolean Function Analysis etc will be taught by Nitin Saurabh during Oct - Nov. See https://nitinsau.github.io/CT-m21-iiith.html



## Prerequisites
Assumes basic knowledge of Discrete Maths, Linear Algebra, Probability, and Algorithms. Highly recomended to brush up these concepts. Some references are given bellow:

- Chapter 1. Mathematical Background, Intro. to TCS, Boaz Barak.
  https://files.boazbarak.org/introtcs/lnotes_book.pdf  
  We will be assuming that you have read this chapter fully and will have an assignment based on it in the first week.
    
- Mathematics for Computer Science. MIT OCW course.  
  https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/resource-index/  
  This is a good long reference. You can brush topics selectively based on need. 



## Schedule


### Meetings
From 15th August - 30th September, 2021

- **Live Lectures**: Tuesday, Friday (5:00 pm - 6:30 pm)
- **Tutorials**: Saturday (2:30 pm -4:00 pm)
- **Office Hours**: Wednesday, 3-430PM. I will be available on Teams during the timings given bellow, for clearing any doubts. 
You can sent a direct message to me for joining.

### Expected Workload
Students are expected to spent atleast 12 hrs per week. Roughly
- 3+1 hrs attending lectures and tutorials
- 4 hrs reading textbooks, references etc 
- 4 hrs solving assignments, quizes etc

### Evaluations
- **4 Light Quizzes** (Wieghtage: 30%, Best 3 of 4). 20 min MCQ Test to check your understanding of definitions and to ensure that you have gone through reading material.
  - 28 August and 4, 18, 25 September.  
- **3  Assignments** (Wieghtage: 30%, ^Best 5 of 6). Problems will require longer to solve. You will need to upload written solutions. One of the assignments which will be harder can be assigned to a group of students. Groups will be formed by the instructors.      
  Dates for Release | Submission | Marks Release given bellow: 
  1. 20 Aug | 30 Aug | 10 Sept  
  2. 30 Aug | 10 Sept | 20 Sept  
  3. 10 Aug | 20 Sept | 30 Sept  (Group Assignment)   
^There will be 3 more assignments in the Part II.
  <!-- 4. 11 Sept | 22 Sept | 29 Sept    -->
- **2 Deep Quizzes** (Wieghtage: 30%, ^Best 3 of 4). We will be doing timed exams of 1hr in moodle.
  1. Between 6-8 Sept | Mark release by 18th Sept.
  2. 30th Sept | Marks release by 10th Oct.  
^There will be 2 more in the Part II.
- **Scribe Notes or Presentations** (Wieghtage: 10%). Students will be given a choice to scribe notes for a lecture or do presentations on an advanced topic. They will be evaluated on clarity of explaining the concepts. Some of the topics for presentation are listed bellow:
  1. PAC Learning and Sample Complexity
  2. Property Testing
  3. One Way functions in Cryptography
  4. Communication Complexity

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Your intelligence cannot be measured by just a number. It is defined by your willingness to learn, solve problems and try new things.<br><br>You are more than just a number. Develop your skills wherever they may lead. Share your ideas. Your skills are more valuable than your grades. 🧠</p>&mdash; Prof. Feynman (@ProfFeynman) <a href="https://twitter.com/ProfFeynman/status/1382170602467856384?ref_src=twsrc%5Etfw">April 14, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


## Lectures

### 1. Computational Models, Encoding of Problems

#### 1.1 Motivations
- Read:
  - For Multiplication Algorithms see Chapter 0 in [Barak](https://files.boazbarak.org/introtcs/lnotes_book.pdf)
  - For Euler, Hamiltonian paths see https://www.cs.sfu.ca/~ggbaker/zju/math/euler-ham.html
  - For more on Representation of Mathematical Objects see Chapter 2 in [Barak](https://files.boazbarak.org/introtcs/lnotes_book.pdf)
- [Assignment 1](problems.pdf)
  Deadline Aug 30th.

#### 1.2 Representations, Prefix Free Encoding, Turing Machine Model, Encoding TMs
 - [Notes](lec2.pdf)
 - Read:
  - For more on Representation of Mathematical Objects see Chapter 2 in [Barak](https://files.boazbarak.org/introtcs/lnotes_book.pdf)
  - Sections 1.2, 1.3 in [Arora, Barack](https://theory.cs.princeton.edu/complexity/book.pdf)
 - Explore:
   - https://turingmachinesimulator.com/
  
#### 1.3 Robustness of definitions

### 2. Complexity Measures and Classes

#### 2.1 Complexity Measure and Classes
#### 2.2 Non determinism, Savitch's Theorem
#### 2.3 Nonuniform Computation, P/poly

### 3. Impossiblity Results

#### 3.1 Universal TM, Halting Problem

#### 3.2 Time, Space hiearchy

#### 3.3 Shannon's Counting Lowerboud for Circuits, P/poly has undecidable problems.

### 4. Reductions and Completeness

#### 4.1 NP-Completeness, Reductions

#### 4.2 Cook-Levin Theorem

#### 4.3 Complexity of Counting (if time permits)



## Textbook and References


- S. Arora and B. Barak (2000), Computational Complexity: A Modern Approach, Cambridge University Press.   
  https://theory.cs.princeton.edu/complexity/book.pdf  
- [Barak] B. Barak, Introduction to Theoretical Computer Science.  
  https://files.boazbarak.org/introtcs/lnotes_book.pdf  
  https://introtcs.org/public/index.html
- A. Wigderson, Mathematics and Computation.  
  https://www.math.ias.edu/files/Book-online-Aug0619.pdf#page=1
- C. Moore & S. Mertens (2011), The Nature of Computation, Oxford University Press.  
- M. Sipser (2014), Introduction to Theory of Computation, Cengange Learning. 
- C. Papadimitriou (1994), Computational Complexity, Addison Wesley Longman.

