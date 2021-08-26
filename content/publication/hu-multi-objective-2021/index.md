---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multi-objective Neural Architecture Search with Almost No Training
subtitle: ''
summary: ''
authors:
- Shengran Hu
- Ran Cheng
- Cheng He
- Zhichao Lu
tags:
- '"Neural architecture search"'
- '"Evolutionary algorithms"'
- '"Multi-objective optimization"'
- '"Performance estimation"'
categories: []
date: '2021-01-01'
lastmod: 2021-08-27T07:59:34+08:00
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
publishDate: '2021-08-26T23:59:34.324294Z'
publication_types:
- '1'
abstract: In the recent past, neural architecture search (NAS) has attracted increasing
  attention from both academia and industries. Despite the steady stream of impressive
  empirical results, most existing NAS algorithms are computationally prohibitive
  to execute due to the costly iterations of stochastic gradient descent (SGD) training.
  In this work, we propose an effective alternative, dubbed Random-Weight Evaluation
  (RWE), to rapidly estimate the performance of network architectures. By just training
  the last linear classification layer, RWE reduces the computational cost of evaluating
  an architecture from hours to seconds. When integrated within an evolutionary multi-objective
  algorithm, RWE obtains a set of efficient architectures with state-of-the-art performance
  on CIFAR-10 with less than two hours’ searching on a single GPU card. Ablation studies
  on rank-order correlations and transfer learning experiments to ImageNet have further
  validated the effectiveness of RWE.
publication: '*Evolutionary Multi-Criterion Optimization*'
doi: 10.1007/978-3-030-72062-9_39
---
