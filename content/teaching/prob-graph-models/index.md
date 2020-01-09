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
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
Probabilistic Graphical Models refers to concise representations of probability distributions using graphs.
It also studies efficient algorithms for sampling distributions represented in such form. Sampling might need to be done from
the joint probability distribution, the marginals or even conditional distributions. Other algorithmic questions involve computing
the Maximum Likelihood Estimate (MLE), Maximum Aposteriori Estimate (MAP) etc. This topic has deep connections and applications to various
fields including Theoretical Computer Science, Machine Learning, Statistical Physics, Bioinformatics etc. We will also be covering analysis of Markov Chain Monte Carlo (MCMC) Algorithms and touch upon probabilistic analysis in learning theory (PAC Learning) as well as Spectral Graph Theory. If time permits, we will look at novel representations of probability distributions like Normalizing Flows which has found some success in generative modeling in Machine Learning.

[Draft Syllabus](pgm_syllabus.pdf)

## Grading

## Lectures

## Textbook and References

- [KE] [Probabilistic Graphical Models, Course Notes](https://ermongroup.github.io/cs228-notes/)
  Volodymyr Kuleshov and Stefano Ermon

- [KF] Probabilistic Graphical Models: Principles and Techniques
  Daphne Koller and Nir Friedman, MIT Press (2009).

- [KM] Machine Learning: a Probabilistic Perspective
  by Kevin Patrick Murphy

- [WJ] [Graphical Models, Exponential Families, and Variational Inference](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf)  Martin J. Wainwright and Michael I. Jordan

- [MM] [Information, Physics, and Computation](https://web.stanford.edu/~montanar/RESEARCH/book.html)
  Marc Mézard and Andrea Montanari
