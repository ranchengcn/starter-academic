---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Efficient Approach to Nondominated Sorting for Evolutionary Multiobjective
  Optimization
subtitle: ''
summary: ''
authors:
- Xingyi Zhang
- Ye Tian
- Ran Cheng
- Yaochu Jin
tags:
- '"Optimization"'
- '"Sociology"'
- '"Statistics"'
- '"Sorting"'
- '"Time complexity"'
- '"evolutionary multiobjective optimization"'
- '"nondominated sorting"'
- '"Algorithm design and analysis"'
- '"Computational complexity"'
- '"Pareto-optimality"'
categories: []
date: '2015-04-01'
lastmod: 2021-08-03T13:11:41+08:00
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
publishDate: '2021-08-03T05:11:41.582738Z'
publication_types:
- '2'
abstract: Evolutionary algorithms have been shown to be powerful for solving multiobjective
  optimization problems, in which nondominated sorting is a widely adopted technique
  in selection. This technique, however, can be computationally expensive, especially
  when the number of individuals in the population becomes large. This is mainly because
  in most existing nondominated sorting algorithms, a solution needs to be compared
  with all other solutions before it can be assigned to a front. In this paper we
  propose a novel, computationally efficient approach to nondominated sorting, termed
  efficient nondominated sort (ENS). In ENS, a solution to be assigned to a front
  needs to be compared only with those that have already been assigned to a front,
  thereby avoiding many unnecessary dominance comparisons. Based on this new approach,
  two nondominated sorting algorithms have been suggested. Both theoretical analysis
  and empirical results show that the ENS-based sorting algorithms are computationally
  more efficient than the state-of-the-art nondominated sorting methods.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2014.2308305
---
