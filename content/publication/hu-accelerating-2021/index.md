---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Accelerating multi-objective neural architecture search by random-weight evaluation
subtitle: ''
summary: ''
authors:
- Shengran Hu
- Ran Cheng
- Cheng He
- Zhichao Lu
- Jing Wang
- Miao Zhang
tags:
- Evolutionary algorithm
- Multi-objective optimization
- Neural architecture search
- Efficient performance estimation
categories: []
date: '2021-12-01'
lastmod: 2023-03-16T12:30:50+08:00
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
publishDate: '2023-03-16T04:30:50.471551Z'
publication_types:
- '2'
abstract: For the goal of automated design of high-performance deep convolutional
  neural networks (CNNs), neural architecture search (NAS) methodology is becoming
  increasingly important for both academia and industries. Due to the costly stochastic
  gradient descent training of CNNs for performance evaluation, most existing NAS
  methods are computationally expensive for real-world deployments. To address this
  issue, we first introduce a new performance estimation metric, named random-weight
  evaluation (RWE) to quantify the quality of CNNs in a cost-efficient manner. Instead
  of fully training the entire CNN, the RWE only trains its last layer and leaves
  the remainders with randomly initialized weights, which results in a single network
  evaluation in seconds. Second, a complexity metric is adopted for multi-objective
  NAS to balance the model size and performance. Overall, our proposed method obtains
  a set of efficient models with state-of-the-art performance in two real-world search
  spaces. Then the results obtained on the CIFAR-10 dataset are transferred to the
  ImageNet dataset to validate the practicality of the proposed algorithm. Moreover,
  ablation studies on NAS-Bench-301 datasets reveal the effectiveness of the proposed
  RWE in estimating the performance compared to existing methods.
publication: '*Complex & Intelligent Systems*'
doi: 10.1007/s40747-021-00594-5
links:
- name: URL
  url: https://doi.org/10.1007/s40747-021-00594-5
---
