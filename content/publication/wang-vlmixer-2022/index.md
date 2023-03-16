---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'VLMixer: Unpaired Vision-Language Pre-training via Cross-Modal CutMix'
subtitle: ''
summary: ''
authors:
- Teng Wang
- Wenhao Jiang
- Zhichao Lu
- Feng Zheng
- Ran Cheng
- Chengguo Yin
- Ping Luo
tags: []
categories: []
date: '2022-06-01'
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
publishDate: '2023-03-16T04:30:50.145901Z'
publication_types:
- '1'
abstract: Existing vision-language pre-training (VLP) methods primarily rely on paired
  image-text datasets, which are either annotated by enormous human labors or crawled
  from the internet followed by elaborate data cleaning techniques. To reduce the
  dependency on well-aligned image-text pairs, it is promising to directly leverage
  the large-scale text-only and image-only corpora. This paper proposes a data augmentation
  method, namely cross-modal CutMix (CMC), for implicit cross-modal alignment learning
  in unpaired VLP. Specifically, CMC transforms natural sentences in the textual view
  into a multi-modal view, where visually-grounded words in a sentence are randomly
  replaced by diverse image patches with similar semantics. There are several appealing
  proprieties of the proposed CMC. First, it enhances the data diversity while keeping
  the semantic meaning intact for tackling problems where the aligned data are scarce;
  Second, by attaching cross-modal noise on uni-modal data, it guides models to learn
  token-level interactions across modalities for better denoising. Furthermore, we
  present a new unpaired VLP method, dubbed as VLMixer, that integrates CMC with contrastive
  learning to pull together the uni-modal and multi-modal views for better instance-level
  alignments among different modalities. Extensive experiments on five downstream
  tasks show that VLMixer could surpass previous state-of-the-art unpaired VLP methods.
publication: '*Proceedings of the 39th International Conference on Machine Learning*'
links:
- name: URL
  url: https://proceedings.mlr.press/v162/wang22h.html
---
