---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Feature Selection for High-dimensional Classification Using a Competitive Swarm
  Optimizer
subtitle: ''
summary: ''
authors:
- Shenkai Gu
- Ran Cheng
- Yaochu Jin
tags: []
categories: []
date: '2018-01-01'
lastmod: 2023-03-16T12:30:23+08:00
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
publishDate: '2023-03-16T04:30:23.599952Z'
publication_types:
- '2'
abstract: When solving many machine learning problems such as classification, there
  exists a large number of input features. However, not all features are relevant
  for solving the problem, and sometimes, including irrelevant features may deteriorate
  the learning performance.Please check the edit made in the article title Therefore,
  it is essential to select the most relevant features, which is known as feature
  selection. Many feature selection algorithms have been developed, including evolutionary
  algorithms or particle swarm optimization (PSO) algorithms, to find a subset of
  the most important features for accomplishing a particular machine learning task.
  However, the traditional PSO does not perform well for large-scale optimization
  problems, which degrades the effectiveness of PSO for feature selection when the
  number of features dramatically increases. In this paper, we propose to use a very
  recent PSO variant, known as competitive swarm optimizer (CSO) that was dedicated
  to large-scale optimization, for solving high-dimensional feature selection problems.
  In addition, the CSO, which was originally developed for continuous optimization,
  is adapted to perform feature selection that can be considered as a combinatorial
  optimization problem. An archive technique is also introduced to reduce computational
  cost. Experiments on six benchmark datasets demonstrate that compared to the canonical
  PSO-based and a state-of-the-art PSO variant for feature selection, the proposed
  CSO-based feature selection algorithm not only selects a much smaller number of
  features, but result in better classification performance as well.
publication: '*Soft Computing*'
doi: 10.1007/s00500-016-2385-6
links:
- name: URL
  url: https://doi.org/10.1007/s00500-016-2385-6
---
