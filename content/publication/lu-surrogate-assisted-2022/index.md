---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Surrogate-assisted Multiobjective Neural Architecture Search for Real-time
  Semantic Segmentation
subtitle: ''
summary: ''
authors:
- Zhichao Lu
- Ran Cheng
- Shihua Huang
- Haoming Zhang
- Changxiao Qiu
- Fan Yang
tags:
- Computational modeling
- Computer architecture
- Evolutionary Algorithm
- Feature extraction
- Image classification
- Multi-objective Optimization
- Neural Architecture Search
- Predictive models
- Real-time systems
- Semantic Segmentation
- Task analysis
categories: []
date: '2022-01-01'
lastmod: 2023-03-16T13:01:14+08:00
featured: true
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
publishDate: '2023-03-16T05:01:13.745732Z'
publication_types:
- '2'
abstract: 'The architectural advancements in deep neural networks have led to remarkable
  leap-forwards across a broad array of computer vision tasks. Instead of relying
  on human expertise, neural architecture search (NAS) has emerged as a promising
  avenue towards automating the design of architectures. While recent achievements
  on image classification have suggested opportunities, the promises of NAS have yet
  to be thoroughly assessed on more challenging tasks of semantic segmentation. The
  main challenges of applying NAS to semantic segmentation arise from two aspects:
  i) high-resolution images to be processed; ii) additional requirement of real-time
  inference speed (i.e. real-time semantic segmentation) for applications such as
  autonomous driving. To meet such challenges, we propose a surrogate-assisted multi-objective
  method in this paper. Through a series of customized prediction models, our method
  effectively transforms the original NAS task to an ordinary multi-objective optimization
  problem. Followed by a hierarchical pre-screening criterion for in-fill selection,
  our method progressively achieves a set of efficient architectures trading-off between
  segmentation accuracy and inference speed. Empirical evaluations on three benchmark
  datasets together with an application using Huawei Atlas 200 DK suggest that our
  method can identify architectures significantly outperforming existing state-of-the-art
  architectures designed both manually by human experts and automatically by other
  NAS methods. Code is available from https://github.com/mikelzc1990/nas-semantic-segmentation.'
publication: '*IEEE Transactions on Artificial Intelligence*'
doi: 10.1109/TAI.2022.3213532
---
