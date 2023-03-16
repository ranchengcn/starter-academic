---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Reference Vector-Assisted Adaptive Model Management for Surrogate-Assisted
  Many-Objective Optimization
subtitle: ''
summary: ''
authors:
- Qiqi Liu
- Ran Cheng
- Yaochu Jin
- Martin Heiderich
- Tobias Rodemann
tags:
- Evolutionary computation
- Optimization
- Convergence
- Search problems
- Linear programming
- Adaptation models
- Computational modeling
- reference vector
- Evolutionary many-objective optimization
- Gaussian process (GP)
- independent and identically distributed (IID)
- surrogate-assisted evolutionary algorithms (SAEAs)
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
publishDate: '2023-03-16T04:30:49.507861Z'
publication_types:
- '2'
abstract: Acquisition functions for surrogate-assisted many-objective optimization
  require a delicate balance between convergence and diversity. However, the conflicting
  nature between many objectives may lead to an imbalance between exploration and
  exploitation, resulting in a low efficiency in search for a set of optimal solutions
  that can well balance convergence and diversity. To meet this challenge, we propose
  an adaptive model management strategy assisted by two sets of reference vectors,
  one set of adaptive reference vectors accounting for convergence while the other
  set of fixed reference vectors for diversity. Specifically, we first propose a new
  acquisition function that calculates an amplified upper confidence bound (AUCB).
  Two optimization processes are performed in parallel to optimize the acquisition
  function, each based on one of the two sets of reference vectors. Then, we select
  one promising candidate solution according to diversity or convergence from the
  nondominated solutions obtained by the two optimization processes. The experimental
  results on four suites of test functions as well as six real-world application problems
  demonstrate the competitive performance of the proposed reference vector-assisted
  adaptive model management strategy, in comparison with seven state-of-the-art surrogate-assisted
  evolutionary algorithms (SAEAs).
publication: '*IEEE Transactions on Systems, Man, and Cybernetics: Systems*'
doi: 10.1109/TSMC.2022.3163129
---
