---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A benchmark generator for online dynamic single-objective and multi-objective
  optimization problems
subtitle: ''
summary: ''
authors:
- Xiaoshu Xiang
- Ye Tian
- Ran Cheng
- Xingyi Zhang
- Shengxiang Yang
- Yaochu Jin
tags:
- Benchmark generator
- Dynamic vehicle routing problems
- Online dynamic optimization
categories: []
date: '2022-10-01'
lastmod: 2023-03-16T12:30:51+08:00
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
publishDate: '2023-03-16T04:30:51.109470Z'
publication_types:
- '2'
abstract: In the past years, a number of benchmarks have been developed to characterize
  dynamic optimization problems (DOPs) consisting of a series of static problems over
  time. The solutions found for a static problem in a previous environment are required
  to be completely implemented so that the static problems in future environments
  are independent of the implementation of the solutions in the previous environment.
  Nevertheless, there is a wide range of real-world DOPs in which the problems in
  future environments are considerably influenced by the components of the solutions
  that are not implemented in previous environments, since the optimization for the
  problem in each environment continuously proceeds while the solutions are continuously
  implemented until the end of a working day or makespan. This type of DOPs can be
  termed as an online DOP (OL-DOP). To compensate for the lack of a systematical OL-DOP
  test suite, in this study we propose a benchmark generator for online dynamic single-objective
  and multi-objective optimization problems. Specifically, different types of influences
  of the solutions found in each environment on the problems in the next environment
  can be adjusted by different types of functions, and the dynamism degree can be
  tuned by a set of predefined parameters in these functions. Based on the proposed
  generator, we suggest a test suite consisting of ten continuous OL-DOPs and two
  discrete OL-DOPs. The empirical results demonstrate that the suggested OL-DOP test
  suite is characterized by time-deception in comparison with existing DOP benchmark
  test suites, and is able to analyze the ability of dynamic optimization algorithms
  in tackling the influence of the solutions found in each environment on the problem
  in the succeeding environment.
publication: '*Information Sciences*'
doi: 10.1016/j.ins.2022.09.049
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0020025522010957
---
