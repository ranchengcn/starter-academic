---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Solving Incremental Optimization Problems via Cooperative Coevolution
subtitle: ''
summary: ''
authors:
- Ran Cheng
- Mohammad Nabi Omidvar
- Amir H. Gandomi
- Bernhard Sendhoff
- Stefan Menzel
- Xin Yao
tags:
- '"Optimization"'
- '"Benchmark testing"'
- '"Computer science"'
- '"Linear programming"'
- '"Generators"'
- '"Aerodynamics"'
- '"Cooperative coevolution (CC)"'
- '"experience-based optimization"'
- '"incremental optimization problem (IOP)"'
- '"Signal generators"'
- '"variable grouping"'
categories: []
date: '2019-01-01'
lastmod: 2021-08-27T07:59:39+08:00
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
publishDate: '2021-08-27T06:00:37.971165Z'
publication_types:
- '2'
abstract: Engineering designs can involve multiple stages, where at each stage, the
  design models are incrementally modified and optimized. In contrast to traditional
  dynamic optimization problems, where the changes are caused by some objective factors,
  the changes in such incremental optimization problems (IOPs) are usually caused
  by the modifications made by the decision makers during the design process. While
  existing work in the literature is mainly focused on traditional dynamic optimization,
  little research has been dedicated to solving such IOPs. In this paper, we study
  how to adopt cooperative coevolution to efficiently solve a specific type of IOPs,
  namely, those with increasing decision variables. First, we present a benchmark
  function generator on the basis of some basic formulations of IOPs with increasing
  decision variables and exploitable modular structure. Then, we propose a contribution-based
  cooperative coevolutionary framework coupled with an incremental grouping method
  for dealing with them. On one hand, the benchmark function generator is capable
  of generating various benchmark functions with various characteristics. On the other
  hand, the proposed framework is promising in solving such problems in terms of both
  optimization accuracy and computational efficiency. In addition, the proposed method
  is further assessed using a real-world application, i.e., the design optimization
  of a stepped cantilever beam.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2018.2883599
---
