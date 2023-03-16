---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Evolutionary Large-Scale Dynamic Optimization Using Bilevel Variable Grouping
subtitle: ''
summary: ''
authors:
- Hui Bai
- Ran Cheng
- Danial Yazdani
- Kay Chen Tan
- Yaochu Jin
tags:
- Sociology
- Optimization
- Statistics
- Heuristic algorithms
- multipopulation
- Resource management
- variable grouping
- Computational resources allocation
- cooperative coevolution (CC)
- dynamic optimization
- Dynamic scheduling
- large-scale optimization problems
- Vehicle dynamics
categories: []
date: '2022-01-01'
lastmod: 2023-03-16T12:30:49+08:00
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
publishDate: '2023-03-16T04:30:49.182931Z'
publication_types:
- '2'
abstract: Variable grouping provides an efficient approach to large-scale optimization,
  and multipopulation strategies are effective for both large-scale optimization and
  dynamic optimization. However, variable grouping is not well studied in large-scale
  dynamic optimization when cooperating with multipopulation strategies. Specifically,
  when the numbers/sizes of the variable subcomponents are large, the performance
  of the algorithms will be substantially degraded. To address this issue, we propose
  a bilevel variable grouping (BLVG)-based framework. First, the primary grouping
  applies a state-of-the-art variable grouping method based on variable interaction
  analysis to group the variables into subcomponents. Second, the secondary grouping
  further groups the subcomponents into variable cells, that is, combination variable
  cells and decomposition variable cells. We then tailor a multipopulation strategy
  to process the two types of variable cells efficiently in a cooperative coevolutionary
  (CC) way. As indicated by the empirical study on large-scale dynamic optimization
  problems (DOPs) of up to 300 dimensions, the proposed framework outperforms several
  state-of-the-art frameworks for large-scale dynamic optimization.
publication: '*IEEE Transactions on Cybernetics*'
doi: 10.1109/TCYB.2022.3164143
---
