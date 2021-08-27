---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'FaPN: Feature-aligned Pyramid Network for Dense Image Prediction'
subtitle: ''
summary: ''
authors:
- Shihua Huang
- Zhichao Lu
- Ran Cheng
- Cheng He
tags:
- '"Computer Science - Computer Vision and Pattern Recognition"'
categories: []
date: '2021-08-01'
lastmod: 2021-08-27T07:59:44+08:00
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
publishDate: '2021-08-27T01:55:20.224866Z'
publication_types:
- '2'
abstract: Recent advancements in deep neural networks have made remarkable leap-forwards
  in dense image prediction. However, the issue of feature alignment remains as neglected
  by most existing approaches for simplicity. Direct pixel addition between upsampled
  and local features leads to feature maps with misaligned contexts that, in turn,
  translate to mis-classifications in prediction, especially on object boundaries.
  In this paper, we propose a feature alignment module that learns transformation
  offsets of pixels to contextually align upsampled higher-level features; and another
  feature selection module to emphasize the lower-level features with rich spatial
  details. We then integrate these two modules in a top-down pyramidal architecture
  and present the Feature-aligned Pyramid Network (FaPN). Extensive experimental evaluations
  on four dense prediction tasks and four datasets have demonstrated the efficacy
  of FaPN, yielding an overall improvement of 1.2 - 2.6 points in AP / mIoU over FPN
  when paired with Faster / Mask R-CNN. In particular, our FaPN achieves the state-of-the-art
  of 56.7% mIoU on ADE20K when integrated within Mask-Former. The code is available
  from https://github.com/EMI-Group/FaPN.
publication: '*arXiv:2108.07058 [cs]*'
url_pdf: http://arxiv.org/abs/2108.07058
---
