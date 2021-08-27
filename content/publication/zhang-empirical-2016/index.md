---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Empirical Analysis of a Tree-based Efficient Non-dominated Sorting Approach
  for Many-objective Optimization
subtitle: ''
summary: ''
authors:
- Xingyi Zhang
- Ye Tian
- Ran Cheng
- Yaochu Jin
tags:
- '"Computer science"'
- '"Optimization"'
- '"Sociology"'
- '"Sorting"'
- '"Statistics"'
- '"Time complexity"'
categories: []
date: '2016-01-01'
lastmod: 2021-08-27T07:59:30+08:00
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
publishDate: '2021-08-27T01:55:07.171077Z'
publication_types:
- '1'
abstract: Non-dominated sorting has been widely adopted in evolutionary multi-objective
  optimization. Many approaches to non-dominated sorting have been proposed to improve
  its computational efficiency, but unfortunately, most of them still suffer from
  high computational cost, especially when the number of objectives becomes large.
  A tree-based efficient non-dominated sorting approach, termed T-ENS, has been recently
  developed by us for many-objective optimization, where a tree structure is adopted
  to represent solutions, such that the non-dominance relationship between solutions
  can be easily inferred from the position of the solutions in the tree, thereby considerably
  reducing the number of comparisons between solutions belonging to the same non-dominated
  front. To validate the computational efficiency of T-ENS, this paper provides a
  detailed empirical analysis by comparing T-ENS with the state-of-the-art approaches,
  in particular when the number of objectives is larger than three and the population
  size becomes large. Empirical results indicate that the T-ENS is well suited for
  evolutionary many-objective optimization and large-scale multi-objective optimization,
  where either the number of objectives or the population size is large.
publication: '*2016 IEEE Symposium Series on Computational Intelligence (SSCI)*'
doi: 10.1109/SSCI.2016.7850210
---
