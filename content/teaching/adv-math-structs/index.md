+++
# Date this page was created.
date = "2019-29-07"

# Project title.
title = "Advanced Mathematical Structures"

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["mathematics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

The course contains a broad set of intermediate and advanced level topics in Algebra and Combinatorics. The course is intended to: i.) refresh the basic topics learnt in S1-S4 ii.) solve advanced problems on the basic topics iii.) introduce some newer topics which was not covered in S1-S4.


## Grading
- Assignment Tests: 20%
  - Practice problems will be given after each lecture.
  - There will be a test based on practice problems once in a quarter (4 in total) with 5 marks each.

- Quiz 1, Quiz 2: 10% each
  - Weight: 10% each

- MidSem: 25%

- EndSem: 35%

- Bonus Marks: 5%


## Lectures

- **Lec 1: Operator | Associativity | Groups | Subgroups | Integer Subgroups | Cyclic Groups**
    - Read: [MA] Chapter 2, Section 1,2. [TJ] Chapter 3, 4
    - Solve:
        1. Prove that there is a unique Identity element for any group.
        2. [MA] Chapter 2 Exercies, Section 1 Question 5, Section 2 (Page 70) Question 10
        3. [TJ] Section 3.4: Problems 2, 10

- **Lec 2: Burnside / Polya Counting**
    - Read: [JM] Chapter 22, 23.
      https://www.math.cmu.edu/~af1p/Teaching/Combinatorics/Slides/Polya.pdf
    - Solve: [JM] 23.4 Exercises (Lecture 23), 1, 3

3. **Lec 3: Isomorphisms | Homomorphisms | Cosets | Legrange's Theorem | Fermat Little Theorem | FLT Proof using Polya Counting**
    - Read: [MA] Chapter 2, Section 3, 4, 5, 6.
      For FLT Proof using Polya Counting: https://keriimov.wordpress.com/2015/05/24/a-combinatorial-proof-for-fermats-little-theorem-2/
    - Solve:
        1. If G has no proper subgroups then show that G is cyclic of order p, where p is a prime number.
        2. If G is not a cyclic group then show that G has a proper subgroup (ie not {0} or G itself).
        3. A group is called Abelian if the operation is also commutative. Prove that
            1. Every finite cyclic group has to be an Abelian Group
            2. Give an example of a finite Abelian Group that is not cyclic.
        4. ZpxZq is the product of the two sets with pq elements. Addition is defined coordinate wise. Prove that:
            1. ZpxZq is a group.
            2. Show that if p, q is coprime (ie has gcd = 1) then ZpxZq is isomorphic to Zpq

4. **Lec 4: Counting | 12 fold way of Counting Balls and Bins**
    - Read: [CoCo] Sections 1 - 1.5.2
    - Solve:
        1. Let \(k1, k2, ...., kn\) be numbers such that ∑ni=1 i * ki = n. Find the number of permutations of [n], with k1 cycles of length 1, k2 cycles of length 2, ..., kn cycles of length n.
Find a generating set of size 2 for Sn. (Need to prove why your set generates Sn).


5. **Lec 5: 12 fold way of Counting Balls and Bins | Permutations | Inversions | Cycle Structure | Transpositions**
    - Read: [CoCo] Sections 1.5.2 - 1.7


5. **Lec 6: Cycle Structure | Parity of Permutation | Derangements | Inclusion Exclusion**
    - Read: [CoCo] Sections 1.7.1, 1.7.2, 1.7.3, Section 2 - 2.1.1.



## Texbook and References

There is no single book covering all the topics. For different lectures, we will be following material from different sources, which will be posted at the course page. Some of the sources that will be used often are:


- [MA] Algebra by M Artin, Prentice-Hall India.

- [TJ] Abstract Algebra: Theory and Applications
  Thomas W. Judson
  http://abstract.ups.edu/download/aata-20180801.pdf

- [CoCo] Lecture Notes, Combinatorics
  Lecture by Torsten Ueckerdt (KIT)
  http://www.math.kit.edu/iag6/lehre/co2015s/media/script.pdf

- [JM] Permutation Puzzles: A Mathematical Perspective.
  Jamie Mulholland
  http://www.sfu.ca/~jtmulhol/math302/notes/302notes-May07-2012.pdf

- Notes on Combinatorics
  Peter J. Cameron
  http://www.maths.qmul.ac.uk/~pjc/notes/comb.pdf

- An Introduction to Combinatorics and Graph Theory
  David Guichard
  https://www.whitman.edu/mathematics/cgt_online/cgt.pdf
