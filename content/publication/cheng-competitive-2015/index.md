---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Competitive Swarm Optimizer for Large Scale Optimization
subtitle: ''
summary: ''
authors:
- Ran Cheng
- Yaochu Jin
tags:
- '"learning"'
- '"Convergence"'
- '"Optimization"'
- '"Vectors"'
- '"Particle swarm optimization"'
- '"Heuristic algorithms"'
- '"Algorithm design and analysis"'
- '"Competition"'
- '"competitive swarm optimizer"'
- '"convergence analysis"'
- '"Cybernetics"'
- '"large scale optimization"'
- '"particle swarm optimization"'
categories: []
date: '2015-02-01'
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
publishDate: '2021-08-03T05:11:41.167975Z'
publication_types:
- '2'
abstract: In this paper, a novel competitive swarm optimizer (CSO) for large scale
  optimization is proposed. The algorithm is fundamentally inspired by the particle
  swarm optimization but is conceptually very different. In the proposed CSO, neither
  the personal best position of each particle nor the global best position (or neighborhood
  best positions) is involved in updating the particles. Instead, a pairwise competition
  mechanism is introduced, where the particle that loses the competition will update
  its position by learning from the winner. To understand the search behavior of the
  proposed CSO, a theoretical proof of convergence is provided, together with empirical
  analysis of its exploration and exploitation abilities showing that the proposed
  CSO achieves a good balance between exploration and exploitation. Despite its algorithmic
  simplicity, our empirical results demonstrate that the proposed CSO exhibits a better
  overall performance than five state-of-the-art metaheuristic algorithms on a set
  of widely used large scale optimization problems and is able to effectively solve
  problems of dimensionality up to 5000.
publication: '*IEEE Transactions on Cybernetics*'
doi: 10.1109/TCYB.2014.2322602
---
