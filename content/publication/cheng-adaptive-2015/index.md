---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adaptive Reference Vector Generation for Inverse Model Based Evolutionary Multiobjective
  Optimization with Degenerate and Disconnected Pareto Fronts
subtitle: ''
summary: ''
authors:
- Ran Cheng
- Yaochu Jin
- Kaname Narukawa
tags:
- '"Inverse modeling"'
- '"Model based evolutionary optimization"'
- '"Multiobjective optimization"'
- '"Reference vectors"'
categories: []
date: '2015-01-01'
lastmod: 2021-08-03T13:11:28+08:00
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
publishDate: '2021-08-03T05:11:27.789858Z'
publication_types:
- '1'
abstract: Inverse model based multiobjective evolutionary algorithm aims to sample
  candidate solutions directly in the objective space, which makes it easier to control
  the diversity of non-dominated solutions in multiobjective optimization. To facilitate
  the process of inverse modeling, the objective space is partitioned into several
  subregions by predefining a set of reference vectors. In the previous work, the
  reference vectors are uniformly distributed in the objective space. Uniformly distributed
  reference vectors, however, may not be efficient for problems that have nonuniform
  or disconnected Pareto fronts. To address this issue, an adaptive reference vector
  generation strategy is proposed in this work. The basic idea of the proposed strategy
  is to adaptively adjust the reference vectors according to the distribution of the
  candidate solutions in the objective space. The proposed strategy consists of two
  phases in the search procedure. In the first phase, the adaptive strategy promotes
  the population diversity for better exploration, while in the second phase, the
  strategy focused on convergence for better exploitation. To assess the performance
  of the proposed strategy, empirical simulations are carried out on two DTLZ benchmark
  problems, namely, DTLZ5 and DTLZ7, which have a degenerate and a disconnected Pareto
  front, respectively. Our results show that the proposed adaptive reference vector
  strategy is promising in tacking multiobjective optimization problems whose Pareto
  front is disconnected.
publication: '*Evolutionary Multi-Criterion Optimization*'
doi: 10.1007/978-3-319-15934-8_9
---
