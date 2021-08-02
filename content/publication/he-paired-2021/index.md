---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Paired Offspring Generation for Constrained Large-Scale Multiobjective Optimization
subtitle: ''
summary: ''
authors:
- Cheng He
- Ran Cheng
- Ye Tian
- Xingyi Zhang
- Kay Chen Tan
- Yaochu Jin
tags:
- '"Constraint handling"'
- '"Convergence"'
- '"evolutionary algorithm (EA)"'
- '"large-scale optimization"'
- '"many-objective optimization"'
- '"multiobjective optimization"'
- '"Optimization"'
- '"Pareto optimization"'
- '"Signal processing algorithms"'
- '"Sociology"'
- '"Statistics"'
categories: []
date: '2021-06-01'
lastmod: 2021-08-02T17:54:57+08:00
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
publishDate: '2021-08-02T09:54:57.341787Z'
publication_types:
- '2'
abstract: Constrained multiobjective optimization problems (CMOPs) widely exist in
  real-world applications, and they are challenging for conventional evolutionary
  algorithms (EAs) due to the existence of multiple constraints and objectives. When
  the number of objectives or decision variables is scaled up in CMOPs, the performance
  of EAs may degenerate dramatically and may fail to obtain any feasible solutions.
  To address this issue, we propose a paired offspring generation-based multiobjective
  EA for constrained large-scale optimization. The general idea is to emphasize the
  role of offspring generation in reproducing some promising feasible or useful infeasible
  offspring solutions. We first adopt a small set of reference vectors for constructing
  several subpopulations with a fixed number of neighborhood solutions. Then, a pairing
  strategy is adopted to determine some pairwise parent solutions for offspring generation.
  Consequently, the pairwise parent solutions, which could be infeasible, may guide
  the generation of well-converged solutions to cross the infeasible region(s) effectively.
  The proposed algorithm is evaluated on CMOPs with up to 1000 decision variables
  and ten objectives. Moreover, each component in the proposed algorithm is examined
  in terms of its effect on the overall algorithmic performance. Experimental results
  on a variety of existing and our tailored test problems demonstrate the effectiveness
  of the proposed algorithm in constrained large-scale multiobjective optimization.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2020.3047835
---
