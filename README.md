# QP Datasets

This repository includes 2 classic QP datasets used in our experiments for PDHCG algorithm.

- Maros–Mészáros benchmark [https://www.cuter.rl.ac.uk/Problems/marmes.html]
- QPLIB [https://qplib.zib.de/]

## Maros–Mészáros Dataset

The Maros–Mészáros dataset, a standard benchmark for convex quadratic programming, comprises 134 problems. We set the algorithm's time limit to 600 seconds for this dataset due to its smaller size.

## QPLIB Dataset

The QPLIB dataset includes various quadratic programming problems, including those with quadratic and integer constraints. 

We filtered and relaxed some of these, collecting 34 problems for our tests. Given the larger size of this dataset compared to Maros–Mészáros, we set the algorithm's time limit to 3600 seconds.