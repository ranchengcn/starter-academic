---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient Evolutionary Search of Attention Convolutional Networks via Sampled
  Training and Node Inheritance
subtitle: ''
summary: ''
authors:
- Haoyu Zhang
- Yaochu Jin
- Ran Cheng
- Kuangrong Hao
tags:
- '"Optimization"'
- '"Sociology"'
- '"Statistics"'
- '"Computer architecture"'
- '"neural architecture search (NAS)"'
- '"Neural networks"'
- '"Training"'
- '"Attention mechanism"'
- '"convolutional neural networks (CNNs)"'
- '"evolutionary optimization"'
- '"Graphics processing units"'
- '"node inheritance"'
categories: []
date: '2021-01-01'
lastmod: 2021-08-27T07:59:36+08:00
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
publishDate: '2021-08-27T06:00:35.505152Z'
publication_types:
- '2'
abstract: The performance of deep neural networks is heavily dependent on its architecture
  and various neural architecture search strategies have been developed for automated
  network architecture design. Recently, evolutionary neural architecture search (EvoNAS)
  has received increasing attention due to the attractive global optimization capability
  of evolutionary algorithms. However, EvoNAS suffers from extremely high computational
  costs because a large number of performance evaluations are usually required in
  evolutionary optimization, and training deep neural networks is itself computationally
  very expensive. To address this issue, this article proposes a computationally efficient
  framework for the evolutionary search of convolutional networks based on a directed
  acyclic graph, in which parents are randomly sampled and trained on each mini-batch
  of training data. In addition, a node inheritance strategy is adopted so that the
  fitness of all offspring individuals can be evaluated without training them. Finally,
  we encode a channel attention mechanism in the search space to enhance the feature
  processing capability of the evolved neural networks. We evaluate the proposed algorithm
  on the widely used datasets, in comparison with 30 state-of-the-art peer algorithms.
  Our experimental results show that the proposed algorithm is not only computationally
  much more efficient but also highly competitive in learning performance.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2020.3040272
---
