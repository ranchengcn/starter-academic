---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Solving Many-Objective Optimization Problems via Multistage Evolutionary Search
subtitle: ''
summary: ''
authors:
- Huangke Chen
- Ran Cheng
- Witold Pedrycz
- Yaochu Jin
tags:
- '"Convergence"'
- '"Evolutionary algorithm"'
- '"Evolutionary computation"'
- '"many-objective optimization"'
- '"multistage optimization"'
- '"Pareto optimization"'
- '"Shape"'
- '"Sociology"'
categories: []
date: '2021-06-01'
lastmod: 2021-08-01T21:34:44+08:00
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
publishDate: '2021-08-01T13:36:46.785702Z'
publication_types:
- '2'
abstract: With the increase in the number of optimization objectives, balancing the
  convergence and diversity in evolutionary multiobjective optimization becomes more
  intractable. So far, a variety of evolutionary algorithms have been proposed to
  solve many-objective optimization problems (MaOPs) with more than three objectives.
  Most of the existing algorithms, however, find difficulties in simultaneously counterpoising
  convergence and diversity during the whole evolutionary process. To address the
  issue, this paper proposes to solve MaOPs via multistage evolutionary search. To
  be specific, a two-stage evolutionary algorithm is developed, where the convergence
  and diversity are highlighted during different search stages to avoid the interferences
  between them. The first stage pushes multiple subpopulations with different weight
  vectors to converge to different areas of the Pareto front. After that, the nondominated
  solutions coming from each subpopulation are selected for generating a new population
  for the second stage. Moreover, a new environmental selection strategy is designed
  for the second stage to balance the convergence and diversity close to the Pareto
  front. This selection strategy evenly divides each objective dimension into a number
  of intervals, and then one solution having the best convergence in each interval
  will be retained. To assess the performance of the proposed algorithm, 48 benchmark
  functions with 7, 10, and 15 objectives are used to make comparisons with five representative
  many-objective optimization algorithms.
publication: '*IEEE Transactions on Systems, Man, and Cybernetics: Systems*'
doi: 10.1109/TSMC.2019.2930737
---
