---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Neural Architecture Search as Multiobjective Optimization Benchmarks: Problem
  Formulation and Performance Assessment'
subtitle: ''
summary: ''
authors:
- Zhichao Lu
- Ran Cheng
- Yaochu Jin
- Kay Chen Tan
- Kalyanmoy Deb
tags:
- Benchmark testing
- Computer architecture
- deep learning
- Deep learning
- Evolutionary multi-objective optimization
- Hardware
- neural architecture search
- Optimization
- Search problems
- Task analysis
categories: []
date: '2022-01-01'
lastmod: 2023-03-16T12:30:52+08:00
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
publishDate: '2023-03-16T04:30:52.060648Z'
publication_types:
- '2'
abstract: 'The ongoing advancements in network architecture design have led to remarkable
  achievements in deep learning across various challenging computer vision tasks.
  Meanwhile, the development of neural architecture search (NAS) has provided promising
  approaches to automating the design of network architectures for lower prediction
  error. Recently, the emerging application scenarios of deep learning (e.g., autonomous
  driving) have raised higher demands for network architectures considering multiple
  design criteria: number of parameters/weights, number of floating-point operations,
  inference latency, among others. From an optimization point of view, the NAS tasks
  involving multiple design criteria are intrinsically multiobjective optimization
  problems; hence, it is reasonable to adopt evolutionary multiobjective optimization
  (EMO) algorithms for tackling them. Nonetheless, there is still a clear gap confining
  the related research along this pathway: on the one hand, there is a lack of a general
  problem formulation of NAS tasks from an optimization point of view; on the other
  hand, there are challenges in conducting benchmark assessments of EMO algorithms
  on NAS tasks. To bridge the gap: (i) we formulate NAS tasks into general multi-objective
  optimization problems and analyze the complex characteristics from an optimization
  point of view; (ii) we present an end-to-end pipeline, dubbed EvoXBench, to generate
  benchmark test problems for EMO algorithms to run efficiently -without the requirement
  of GPUs or Pytorch/Tensorflow; (iii) we instantiate two test suites comprehensively
  covering two datasets, seven search spaces, and three hardware devices, involving
  up to eight objectives. Based on the above, we validate the proposed test suites
  using six representative EMO algorithms and provide some empirical analyses. The
  code of EvoXBench is available at https://github.com/EMI-Group/EvoXBench.'
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2022.3233364
---
