---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adaptive Simulated Binary Crossover for Rotated Multi-objective Optimization
subtitle: ''
summary: ''
authors:
- Linqiang Pan
- Wenting Xu
- Lianghao Li
- Cheng He
- Ran Cheng
tags:
- Crossover operator
- Evolutionary algorithm
- Multi-objective optimization
- Rotated problem
- Variable linkage
categories: []
date: '2021-01-01'
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
publishDate: '2023-03-16T04:30:22.913793Z'
publication_types:
- '2'
abstract: Crossover is a crucial operation for generating promising offspring solutions
  in evolutionary multi-objective optimization. Among various crossover operators,
  the simulated binary crossover (SBX) is the most widely used in evolutionary multi-objective
  optimization. Despite that SBX is effective in solving problems with regular Pareto
  sets, its performance degenerates dramatically on problems with rotated Pareto sets.To
  address this issue, we propose a modified SBX, named the rotation-based simulated
  binary crossover (RSBX), to improve the performance of multi-objective evolutionary
  algorithms (MOEAs) on rotated problems whose Pareto sets are not parallel with the
  decision variables. The main idea is to introduce the rotation property into the
  SBX, and then an adaptive selection strategy is proposed to make use of both SBX
  and RSBX. The proposed method is embedded in three representative MOEAs, and they
  are compared with their original versions on some problems with rotated Pareto sets,
  respectively. Experimental results demonstrate that the proposed method is efficient
  in promoting the performance of conventional MOEAs for handling rotated multi-objective
  optimization problems.
publication: '*Swarm and Evolutionary Computation*'
doi: 10.1016/j.swevo.2020.100759
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S2210650220304120
---
