---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Accelerating Large-Scale Multiobjective Optimization via Problem Reformulation
subtitle: ''
summary: ''
authors:
- Cheng He
- Lianghao Li
- Ye Tian
- Xingyi Zhang
- Ran Cheng
- Yaochu Jin
- Xin Yao
tags:
- Evolutionary computation
- Pareto optimization
- Convergence
- large-scale optimization
- problem reformulation
- multiobjective optimization
- Signal processing algorithms
- Evolutionary algorithms
- Acceleration
- IEEE Fellows
categories: []
date: '2019-01-01'
lastmod: 2023-03-16T12:30:41+08:00
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
publishDate: '2023-03-16T04:30:41.525008Z'
publication_types:
- '2'
abstract: In this paper, we propose a framework to accelerate the computational efficiency
  of evolutionary algorithms on large-scale multiobjective optimization. The main
  idea is to track the Pareto optimal set (PS) directly via problem reformulation.
  To begin with, the algorithm obtains a set of reference directions in the decision
  space and associates them with a set of weight variables for locating the PS. Afterwards,
  the original large-scale multiobjective optimization problem is reformulated into
  a low-dimensional single-objective optimization problem. In the reformulated problem,
  the decision space is reconstructed by the weight variables and the objective space
  is reduced by an indicator function. Thanks to the low dimensionality of the weight
  variables and reduced objective space, a set of quasi-optimal solutions can be obtained
  efficiently. Finally, a multiobjective evolutionary algorithm is used to spread
  the quasi-optimal solutions over the approximate Pareto optimal front evenly. Experiments
  have been conducted on a variety of large-scale multiobjective problems with up
  to 5000 decision variables. Four different types of representative algorithms are
  embedded into the proposed framework and compared with their original versions,
  respectively. Furthermore, the proposed framework has been compared with two state-of-the-art
  algorithms for large-scale multiobjective optimization. The experimental results
  have demonstrated the significant improvement benefited from the framework in terms
  of its performance and computational efficiency in large-scale multiobjective optimization.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2019.2896002
---
