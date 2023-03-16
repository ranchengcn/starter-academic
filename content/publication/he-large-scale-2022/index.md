---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Large-scale Multiobjective Optimization via Reformulated Decision Variable
  Analysis
subtitle: ''
summary: ''
authors:
- Cheng He
- Ran Cheng
- Lianghao Li
- Kay Chen Tan
- Yaochu Jin
tags:
- Convergence
- decision variable analysis
- evolutionary algorithm
- Iron
- Large-scale optimization
- Maintenance engineering
- Optimization
- problem reformulation
- Sociology
- Statistics
- Visualization
categories: []
date: '2022-01-01'
lastmod: 2023-03-16T12:30:52+08:00
featured: false
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
publishDate: '2023-03-16T04:30:51.747267Z'
publication_types:
- '2'
abstract: With the rising number of large-scale multiobjective optimization problems
  (LSMOPs) from academia and industries, some multiobjective evolutionary algorithms
  (MOEAs) with different decision variable handling strategies have been proposed.
  Decision variable analysis (DVA) is widely used in large-scale optimization, aiming
  at identifying the connection between each decision variable and the objectives,
  and grouping those interacting decision variables to reduce the complexity of LSMOPs.
  Despite their effectiveness, existing DVA techniques require the unbearable cost
  of function evaluations for solving LSMOPs. We propose a reformulation based approach
  for efficient DVA to address this deficiency. Then a large-scale MOEA is proposed
  based on reformulated DVA, namely LERD. Specifically, the DVA process is reformulated
  into an optimization problem with binary decision variables, aiming to approximate
  different grouping results. Afterwards, each group of decision variables is used
  for convergence-related or diversity-related optimization. The effectiveness and
  efficiency of the reformulation based DVA are validated by replacing the corresponding
  DVA techniques in two large-scale MOEAs. Experiments in comparison with six state-of-the-art
  large-scale MOEAs on LSMOPs with up to 2000 decision variables have shown the promising
  performance of LERD.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2022.3213006
---
