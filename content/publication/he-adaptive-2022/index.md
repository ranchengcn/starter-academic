---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adaptive Offspring Generation for Evolutionary Large-Scale Multiobjective Optimization
subtitle: ''
summary: ''
authors:
- Cheng He
- Ran Cheng
- Danial Yazdani
tags:
- Evolutionary computation
- Pareto optimization
- Sociology
- Convergence
- multiobjective optimization
- Adaptive offspring generation
- evolutionary algorithm (EA)
- large-scale
- Maintenance engineering
categories: []
date: '2022-02-01'
lastmod: 2023-03-16T12:30:47+08:00
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
publishDate: '2023-03-16T04:30:47.611737Z'
publication_types:
- '2'
abstract: Offspring generation plays an important role in evolutionary multiobjective
  optimization. However, generating promising candidate solutions effectively in high-dimensional
  spaces is particularly challenging. To address this issue, we propose an adaptive
  offspring generation method for large-scale multiobjective optimization. First,
  a preselection strategy is proposed to select a balanced parent population, and
  then these parent solutions are used to construct direction vectors in the decision
  spaces for reproducing promising offspring solutions. Specifically, two kinds of
  direction vectors are adaptively used to generate offspring solutions. The first
  kind takes advantage of the dominated solutions to generate offspring solutions
  toward the Pareto optimal set (PS) for convergence enhancement, while the other
  kind uses those nondominated solutions to spread the solutions over the PS for diversity
  maintenance. The proposed offspring generation method can be embedded in many existing
  multiobjective evolutionary algorithms (EAs) for large-scale multiobjective optimization.
  Experiments are conducted to reveal the mechanism of our proposed adaptive reproduction
  strategy and validate its effectiveness. Experimental results on some large-scale
  multiobjective optimization problems have demonstrated the competitive performance
  of our proposed algorithm in comparison with five state-of-the-art large-scale EAs.
publication: '*IEEE Transactions on Systems, Man, and Cybernetics: Systems*'
doi: 10.1109/TSMC.2020.3003926
---
