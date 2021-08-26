---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Ternary Compression for Communication-Efficient Federated Learning
subtitle: ''
summary: ''
authors:
- Jinjin Xu
- Wenli Du
- Yaochu Jin
- Wangli He
- Ran Cheng
tags:
- '"Computational modeling"'
- '"Collaborative work"'
- '"Communication efficiency"'
- '"Data models"'
- '"deep learning"'
- '"Distributed databases"'
- '"federated learning"'
- '"Quantization (signal)"'
- '"Servers"'
- '"ternary coding."'
- '"Training"'
categories: []
date: '2020-01-01'
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
publishDate: '2021-08-26T23:59:36.282080Z'
publication_types:
- '2'
abstract: Learning over massive data stored in different locations is essential in
  many real-world applications. However, sharing data is full of challenges due to
  the increasing demands of privacy and security with the growing use of smart mobile
  devices and Internet of thing (IoT) devices. Federated learning provides a potential
  solution to privacy-preserving and secure machine learning, by means of jointly
  training a global model without uploading data distributed on multiple devices to
  a central server. However, most existing work on federated learning adopts machine
  learning models with full-precision weights, and almost all these models contain
  a large number of redundant parameters that do not need to be transmitted to the
  server, consuming an excessive amount of communication costs. To address this issue,
  we propose a federated trained ternary quantization (FTTQ) algorithm, which optimizes
  the quantized networks on the clients through a self-learning quantization factor.
  Theoretical proofs of the convergence of quantization factors, unbiasedness of FTTQ,
  as well as a reduced weight divergence are given. On the basis of FTTQ, we propose
  a ternary federated averaging protocol (T-FedAvg) to reduce the upstream and downstream
  communication of federated learning systems. Empirical experiments are conducted
  to train widely used deep learning models on publicly available data sets, and our
  results demonstrate that the proposed T-FedAvg is effective in reducing communication
  costs and can even achieve slightly better performance on non-IID data in contrast
  to the canonical federated learning algorithms.
publication: '*IEEE Transactions on Neural Networks and Learning Systems*'
doi: 10.1109/TNNLS.2020.3041185
---
