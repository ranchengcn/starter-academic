---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Reference Vector Guided Evolutionary Algorithm for Many-Objective Optimization
subtitle: ''
summary: ''
authors:
- Ran Cheng
- Yaochu Jin
- Markus Olhofer
- Bernhard Sendhoff
tags:
- Evolutionary computation
- Pareto optimization
- Sociology
- Convergence
- Linear programming
- evolutionary multiobjective optimization
- Angle-penalized distance (APD)
- convergence
- diversity
- many-objective optimization
- preference articulation
- reference vector
categories: []
date: '2016-01-01'
lastmod: 2023-03-16T12:30:36+08:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-03-16T04:30:35.917195Z'
publication_types:
- '2'
abstract: In evolutionary multiobjective optimization, maintaining a good balance
  between convergence and diversity is particularly crucial to the performance of
  the evolutionary algorithms (EAs). In addition, it becomes increasingly important
  to incorporate user preferences because it will be less likely to achieve a representative
  subset of the Pareto-optimal solutions using a limited population size as the number
  of objectives increases. This paper proposes a reference vector-guided EA for many-objective
  optimization. The reference vectors can be used not only to decompose the original
  multiobjective optimization problem into a number of single-objective subproblems,
  but also to elucidate user preferences to target a preferred subset of the whole
  Pareto front (PF). In the proposed algorithm, a scalarization approach, termed angle-penalized
  distance, is adopted to balance convergence and diversity of the solutions in the
  high-dimensional objective space. An adaptation strategy is proposed to dynamically
  adjust the distribution of the reference vectors according to the scales of the
  objective functions. Our experimental results on a variety of benchmark test problems
  show that the proposed algorithm is highly competitive in comparison with five state-of-the-art
  EAs for many-objective optimization. In addition, we show that reference vectors
  are effective and cost-efficient for preference articulation, which is particularly
  desirable for many-objective optimization. Furthermore, a reference vector regeneration
  strategy is proposed for handling irregular PFs. Finally, the proposed algorithm
  is extended for solving constrained many-objective optimization problems.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2016.2519378
---
