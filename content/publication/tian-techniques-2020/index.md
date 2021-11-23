---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Techniques for Accelerating Multi-Objective Evolutionary Algorithms in PlatEMO
subtitle: ''
summary: ''
authors:
- Ye Tian
- Ran Cheng
- Xingyi Zhang
- Yaochu Jin
tags:
- '"Evolutionary computation"'
- '"Optimization"'
- '"Sociology"'
- '"Statistics"'
- '"Sorting"'
- '"Evolution (biology)"'
- '"Runtime"'
categories: []
date: '2020-01-01'
lastmod: 2021-08-27T07:59:33+08:00
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
publishDate: '2021-11-23T11:20:48.656798Z'
publication_types:
- '1'
abstract: It has been widely recognized that evolutionary computation is one of the
  most effective techniques for solving complex optimization problems. As a group
  of meta-heuristics inspired by nature, the superiority of evolutionary algorithms
  is mainly attributed to the evolution of multiple candidate solutions, which can
  strike a balance between exploration and exploitation. However, the effectiveness
  of evolutionary algorithms is generally at the expense of efficiency, which reduces
  the prevalence of evolutionary algorithms in solving real-world optimization problems.
  In 2017, we proposed the evolutionary multi-objective optimization platform PlatEMO
  to facilitate the use of multi-objective evolutionary algorithms (MOEAs), where
  some delicate techniques were developed to improve the computational efficiency
  of MOEAs. These techniques have not been introduced before, since users need not
  care about them when using existing MOEAs or developing new MOEAs. To deepen the
  understanding of the core mechanisms of PlatEMO, this paper gives a comprehensive
  introduction to these techniques, including new non-dominated sorting approaches,
  matrix calculation, and parallel computing. Several comparative experiments are
  conducted for a quantitative understanding of the efficiency improvement brought
  by these techniques.
publication: '*2020 IEEE Congress on Evolutionary Computation (CEC)*'
doi: 10.1109/CEC48606.2020.9185797
---
