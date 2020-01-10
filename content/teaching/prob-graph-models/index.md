+++
# Date this page was created.
date = "2020-01-02"

# Project title.
title = "Probabilistic Graphical Models"

selected = true


# Project summary to display on homepage.
summary = """Probabilistic Graphical Models refers to  i.) concise representations of probability distributions using graphs ii.) efficient algorithms for sampling distributions represented in such form iii.) learning these representations from data."""

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
projects = ["theory-cs", "machine-learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
Probabilistic Graphical Models refers to concise representations of probability distributions using graphs.
It also studies efficient algorithms for sampling distributions represented in such form. Sampling might need to be done from
the joint probability distribution, the marginals or even conditional distributions. Other algorithmic questions involve computing
the Maximum Likelihood Estimate (MLE), Maximum Aposteriori Estimate (MAP) etc. This topic has deep connections and applications to various
fields including Theoretical Computer Science, Machine Learning, Statistical Physics, Bioinformatics etc. We will also be covering analysis of Markov Chain Monte Carlo (MCMC) Algorithms.

Broadly the course will cover four modules

1. Reperesentations
2. Inference
3. Learning
4. Advanced Topics (More on MCMC Methods, Normalizing Flows, Learning theory)

[Draft Syllabus](pgm_syllabus.pdf)

## Grading

| Type of Eval | --Weightage |
| ------------ | ----------: |
| Quiz 1       |          10 |
| Mid Sem      |          15 |
| Quiz 2       |          10 |
| End Sem      |          25 |
| Assignments  |          20 |
| Project      |          20 |




## Lectures

- **Lec 1: Probability Recap**
  - *Read:* For recalling basics of probability and graph theory, please go through [DB] Chapter 1, 2
  - *Solve:* 
   <sup>sub</sup> For any two distributions $p,q$ on $\\{1, \cdots, n \\}$, show that:  
  $$\max\_{A \subseteq \\{1, \cdots, n\\}} | p(A) - q(A) | = \frac{\sum\_{i=1}^n | p(i) - q(i) |}{2}.$$
  Note that the event $A$ choosen in LHS is a way of distinguishing $p$ from $q$ using $1$ sample in the best possible way. The RHS is the $\ell_1$ norm $\|p - q\|_1$.

- **Lec 2: Belief Networks I**  
   Free parameters in distributions | Conditional Independence reduces parameters | Graph Representation | d-Connectivity and Independence
  - *Read:* [DB] Sections 3.1 - 3.3
  - *Solve:*
      - [DB] Section 3.8 Exercise 24<sup>sub</sup>, 27, 35<sup>sub</sup>.

- **Lec 3: Belief Networks II**

- **Lec 4: Markov Networks**

## Textbook and References

- [DB] [Bayesian Reasoning and Machine Learning](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/090310.pdf).
  David Barber

- [KE] [Probabilistic Graphical Models, Course Notes](https://ermongroup.github.io/cs228-notes/)
  Volodymyr Kuleshov and Stefano Ermon

- [KF] Probabilistic Graphical Models: Principles and Techniques
  Daphne Koller and Nir Friedman, MIT Press (2009).

- [KM] Machine Learning: a Probabilistic Perspective
  by Kevin Patrick Murphy

- [WJ] [Graphical Models, Exponential Families, and Variational Inference](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf)  Martin J. Wainwright and Michael I. Jordan

- [MM] [Information, Physics, and Computation](https://web.stanford.edu/~montanar/RESEARCH/book.html)
  Marc Mézard and Andrea Montanari
