---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Multi-stage Evolutionary Algorithm for Multi-objective Optimization with
  Complex Constraints
subtitle: ''
summary: ''
authors:
- Haiping Ma
- Haoyu Wei
- Ye Tian
- Ran Cheng
- Xingyi Zhang
tags:
- Evolutionary algorithm
- Constrained multi-objective optimization
- Constraint-handling priority
categories: []
date: '2021-01-01'
lastmod: 2023-03-16T12:30:27+08:00
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
publishDate: '2023-03-16T04:30:27.527809Z'
publication_types:
- '2'
abstract: Constrained multi-objective optimization problems (CMOPs) are difficult
  to handle because objectives and constraints need to be considered simultaneously,
  especially when the constraints are extremely complex. Some recent algorithms work
  well when dealing with CMOPs with a simple feasible region; however, the effectiveness
  of most algorithms degrades considerably for CMOPs with complex feasible regions.
  To address this issue, this paper proposes a multi-stage evolutionary algorithm,
  where constraints are added one after the other and handled in different stages
  of evolution. Specifically, in the early stages, the algorithm only considers a
  small number of constraints, which can make the population efficiently converge
  to the potential feasible region with good diversity. As the algorithm moves to
  the later stages, more constraints are considered to search the optimal solutions
  based on the solutions obtained in the previous stages. Furthermore, a strategy
  for sorting the constraint-handling priority according to the impact on the unconstrained
  Pareto front is proposed, which can accelerate the convergence of the algorithm.
  Experimental results on five benchmark suites and three real-world applications
  showed that the proposed algorithm outperforms several state-of-the-art constraint
  multi-objective evolutionary algorithms when dealing with CMOPs, especially for
  problems with complex constraints.
publication: '*Information Sciences*'
doi: 10.1016/j.ins.2021.01.029
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0020025521000566
---
