+++
# Date this page was created.
date = "2021-07-01"

# Project title.
title = "Maths for CS I: Probability and Statistics"

selected = true

# Project summary to display on homepage.
summary = "A first course in probability and statistics with a focus on discrete spaces."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
#projects = ["complexity-theory", "theory-cs"]

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



## Prerequisites
Assumes basic knowledge of Discrete Maths and Algorithms. Highly recomended to brush up these concepts, especially if you had a break from academics. Some references are given bellow:

- Chaper 0,1 in https://www.alextsun.com/files/Prob_Stat_for_CS_Book.pdf.  
  We will be assuming that you have read this chapter fully and will have an assignment based on it in the first week.
    
- Mathematics for Computer Science. MIT OCW course.  
  https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/resource-index/  
  This is a good long reference. You can brush topics selectively based on need. 


## Schedule


### Meetings

From 15th August - 30th September, 2021.  

- **Live Lectures**: Tuesdays and Fridays (12:00 pm - 1:30 pm)  
- **Tutorials**: Wednesday (9-1030AM)
- **Office Hours**: Saturday (2:30 pm -4:00 pm). I will be available on Teams during the timings given bellow, for clearing any doubts. 
You can sent a direct message to me for joining.

### Expected Workload
Students are expected to spent atleast 12 hrs per week. Roughly
- 3+1 hrs attending lectures and tutorials
- 4 hrs reading textbooks, references etc 
- 4 hrs solving assignments, quizes etc

### Evaluations
- **4 Light Quizzes** (Wieghtage: 30%, Best 3 of 4). 20 min MCQ Test to check your understanding of definitions and to ensure that you have gone through reading material.
  - 28 August and 4, 18, 25 September.
- **4  Assignments**  (Wieghtage: 30%, ^Best 3 of 4). Problems will require longer to solve. You will need to upload written solutions.       
  Dates for Release | Submission | Marks Release given bellow: 
  1. 12 Aug | 21 Aug | 28 Aug  
  2. 21 Aug | 31 Aug | 5 Sept  
  3. 31 Aug | 11 Sept | 18 Sept  
  4. 11 Sept | 22 Sept | 29 Sept   
- **2 Deep Quizzes** (Wieghtage: 40%). We will be doing timed exams of 1hr in moodle.
  1. Between 6-8 Sept | Mark release by 18th Sept.
  2. 30th Sept | Marks release by 10th Oct.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Your intelligence cannot be measured by just a number. It is defined by your willingness to learn, solve problems and try new things.<br><br>You are more than just a number. Develop your skills wherever they may lead. Share your ideas. Your skills are more valuable than your grades. 🧠</p>&mdash; Prof. Feynman (@ProfFeynman) <a href="https://twitter.com/ProfFeynman/status/1382170602467856384?ref_src=twsrc%5Etfw">April 14, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


## Lectures

### 1. Probability Basics
#### 1.1 Probability and Counting | Infinite Sample Spaces 
- Reading:
  - Section 1.0 - 1.3 in [HPN](https://www.probabilitycourse.com/).  
  - Secion 1.1 - 1.2 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).
  - Chapter 1 in https://www.math.kit.edu/iag6/lehre/co2015s/media/script.pdf  
- Solve:
  - [Problems](problems.pdf)
#### 1.2 Axioms of Probability | Conditional Probability 
- Reading:
  - Section 1.4, Section 2 in [HPN](https://www.probabilitycourse.com/).  
  - Secion 1.3, 1.6 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).
- Explore:
  - [Cantor's Diagonlization](https://jlmartin.ku.edu/~jlmartin/courses/math410-S09/cantor.pdf)
  - [Continuum Hypothesis](https://en.wikipedia.org/wiki/Continuum_hypothesis)
- Solve:
  - Let $X$ be number of nonempty bins and $Y$ be number of balls in the first bin. Find the probability of 
    1. $X=i, Y=j$ 
    2. $X=i$ conditioned on $Y=j$   
  
    for every $i,j$.

#### 1.3 Conditional Probability | Independence 
- Reading:
  - Section 1.4, Section 2 in [HPN](https://www.probabilitycourse.com/).  
  - Secion 1.3, 1.4 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).

#### 1.4 Total Probability | Bayes' Rule
- Reading:
  - Section 1.4, Section 2 in [HPN](https://www.probabilitycourse.com/). 
  - Secion 1.3, 1.4, 1.5 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).
- Explore:
  - [Infinite Monkey Theorem](https://en.wikipedia.org/wiki/Infinite_monkey_theorem)
  - [Birthday Problem](https://en.wikipedia.org/wiki/Birthday_problem)
  - [Monty Python Game](https://en.wikipedia.org/wiki/Monty_Hall_problem#:~:text=As%20Keith%20Devlin%20says%2C%20%22By,of%20them%20is%2023.)

### 2. Random Variables

#### 2.1 Random Variables | Expectation | Binomial Distrbution | Geometric Dist | Conditioning | Multiple RVs
- Reading:
  - Section 3 in [HPN](https://www.probabilitycourse.com/).
  - Section 2 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).

#### 2.2 Linearity of Expectation | Functions of Random Variables
- Reading:
  - Section 3.2.2-3.2.3 in [HPN](https://www.probabilitycourse.com/).
  - Section 2.3-2.4 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).

#### 2.3 Variance | Markov's | Chebyshev's Inequality
- Reading:
  - Chapter 6 in [AT](https://www.alextsun.com/files/Prob_Stat_for_CS_Book.pdf).

#### 2.4 Problem Solving | Poll Survey
- Reading:
  - Chapter 6 in [AT](https://www.alextsun.com/files/Prob_Stat_for_CS_Book.pdf).

### 3. Advanced Random Variables
#### 3.1 Poisson, Exponential, Continous Distributions
- Reading:
  - Section 3.6, 4.1, 4.2 in [AT](https://www.alextsun.com/files/Prob_Stat_for_CS_Book.pdf).
  - Section 4.1, 4.2 in [HPN](https://www.probabilitycourse.com/).
  - Section 3.1, 3.2, 5.2 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).


#### 3.2 Gaussian Distribution, Central Limit Theorem
- Reading:
  - Section 4.3, 5.7 in [AT](https://www.alextsun.com/files/Prob_Stat_for_CS_Book.pdf).
  - Section 4.2.3, 7 in [HPN](https://www.probabilitycourse.com/).
  - Section 3.3 (Normal Dist), 4.2 (Convolutions), 7.1-7.4 (CLT) in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).


### 4. Advanced Topics and Applications

#### 4.1 Markov Chains
- Reading:
  - Section 11.2 in [HPN](https://www.probabilitycourse.com/).
  - Chapter 6 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).



#### 4.2 Markov Chains Convergence
- Reading:
  - Section 11.2 in [HPN](https://www.probabilitycourse.com/).
  - Chapter 6 in [BT](https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf).



## References

### Textbooks
- [HPN] Introduction to Probability, Statistics and Random Processes. by Hossien Pishro-Nik.  
  https://www.probabilitycourse.com/  
- [BT] Introduction to Probability, 2nd Edition by Dimitri P. Bertsekas and John N. Tsitsiklis. Lecture Notes.  
  https://www.vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf  
- [AT] Probability & Statistics with Applications to Computing by Alex Tsun.  
  https://www.alextsun.com/files/Prob_Stat_for_CS_Book.pdf  
- [WF] An Introduction to Probability Theory and Its Applications, Volume 1 by William Feller.
- [SR] Introduction to Probability and Statistics for Engineers and Scientists by Sheldon M. Ross. Available in Library.

### Online Resources

- Videos from previous course  
  https://www.youtube.com/playlist?list=PLdarCLN35z-ArxfyMolYrY0qCLqwv8jqF  

- Probabilistic Systems Analysis and Applied Probability, MIT Open Course Ware.  
  https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041sc-probabilistic-systems-analysis-and-applied-probability-fall-2013/resource-index/

- A Concrete Introduction to Probability (using Python)  
  https://github.com/norvig/pytudes/blob/main/ipynb/Probability.ipynb  
  https://github.com/norvig/pytudes/blob/main/ipynb/ProbabilityParadox.ipynb  

- 3Blue1Brown Youtube Channel  
  https://www.youtube.com/watch?v=HZGCoVF3YvM

  