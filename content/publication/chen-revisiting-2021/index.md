---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Revisiting Self-Training for Few-Shot Learning of Language Model
subtitle: ''
summary: ''
authors:
- Yiming Chen
- Yan Zhang
- Chen Zhang
- Grandee Lee
- Ran Cheng
- Haizhou Li
tags:
- Computer Science - Computation and Language
categories: []
date: '2021-10-01'
lastmod: 2023-03-16T12:30:46+08:00
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
publishDate: '2023-03-16T04:30:46.665999Z'
publication_types:
- '2'
abstract: As unlabeled data carry rich task-relevant information, they are proven
  useful for few-shot learning of language model. The question is how to effectively
  make use of such data. In this work, we revisit the self-training technique for
  language model fine-tuning and present a state-of-the-art prompt-based few-shot
  learner, SFLM. Given two views of a text sample via weak and strong augmentation
  techniques, SFLM generates a pseudo label on the weakly augmented version. Then,
  the model predicts the same pseudo label when fine-tuned with the strongly augmented
  version. This simple approach is shown to outperform other state-of-the-art supervised
  and semi-supervised counterparts on six sentence classification and six sentence-pair
  classification benchmarking tasks. In addition, SFLM only relies on a few in-domain
  unlabeled data. We conduct a comprehensive analysis to demonstrate the robustness
  of our proposed approach under various settings, including augmentation techniques,
  model scale, and few-shot knowledge transfer across tasks.
publication: '*arXiv:2110.01256 [cs]*'
links:
- name: URL
  url: http://arxiv.org/abs/2110.01256
---
