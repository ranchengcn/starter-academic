---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'RelativeNAS: Relative Neural Architecture Search via Slow-Fast Learning'
subtitle: ''
summary: ''
authors:
- Hao Tan
- Ran Cheng
- Shihua Huang
- Cheng He
- Changxiao Qiu
- Fan Yang
- Ping Luo
tags:
- '"AutoML"'
- '"Computer architecture"'
- '"convolutional neural network (CNN)"'
- '"Estimation"'
- '"neural architecture search (NAS)"'
- '"Neural networks"'
- '"Optimization"'
- '"population-based search"'
- '"Search problems"'
- '"slow-fast learning."'
- '"Sociology"'
- '"Statistics"'
categories: []
date: '2021-01-01'
lastmod: 2021-08-27T07:59:45+08:00
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
publishDate: '2021-08-26T23:59:45.128347Z'
publication_types:
- '2'
abstract: 'Despite the remarkable successes of convolutional neural networks (CNNs)
  in computer vision, it is time-consuming and error-prone to manually design a CNN.
  Among various neural architecture search (NAS) methods that are motivated to automate
  designs of high-performance CNNs, the differentiable NAS and population-based NAS
  are attracting increasing interests due to their unique characters. To benefit from
  the merits while overcoming the deficiencies of both, this work proposes a novel
  NAS method, RelativeNAS. As the key to efficient search, RelativeNAS performs joint
  learning between fast learners (i.e., decoded networks with relatively lower loss
  value) and slow learners in a pairwise manner. Moreover, since RelativeNAS only
  requires low-fidelity performance estimation to distinguish each pair of fast learner
  and slow learner, it saves certain computation costs for training the candidate
  architectures. The proposed RelativeNAS brings several unique advantages: 1) it
  achieves state-of-the-art performances on ImageNet with top-1 error rate of 24.88%,
  that is, outperforming DARTS and AmoebaNet-B by 1.82% and 1.12%, respectively; 2)
  it spends only 9 h with a single 1080Ti GPU to obtain the discovered cells, that
  is, 3.75x and 7875x faster than DARTS and AmoebaNet, respectively; and 3) it provides
  that the discovered cells obtained on CIFAR-10 can be directly transferred to object
  detection, semantic segmentation, and keypoint detection, yielding competitive results
  of 73.1% mAP on PASCAL VOC, 78.7% mIoU on Cityscapes, and 68.5% AP on MSCOCO, respectively.
  The implementation of RelativeNAS is available at https://github.com/EMI-Group/RelativeNAS.'
publication: '*IEEE Transactions on Neural Networks and Learning Systems*'
doi: 10.1109/TNNLS.2021.3096658
---
