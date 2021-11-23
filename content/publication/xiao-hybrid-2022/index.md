---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hybrid attention-based transformer block model for distant supervision relation
  extraction
subtitle: ''
summary: ''
authors:
- Yan Xiao
- Yaochu Jin
- Ran Cheng
- Kuangrong Hao
tags:
- '"Distant supervision relation extraction (DSRE)"'
- '"Sentence-level attention"'
- '"Transformer block"'
categories: []
date: '2022-01-01'
lastmod: 2021-11-23T19:21:34+08:00
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
publishDate: '2021-11-23T11:21:33.676930Z'
publication_types:
- '2'
abstract: With an exponential explosive growth of various digital text information,
  it is challenging to efficiently obtain specific knowledge from massive unstructured
  text information. As one basic task for natural language processing (NLP), relation
  extraction (RE) aims to extract semantic relations between entity pairs based on
  the given text. To avoid manual labeling of datasets, distant supervision relation
  extraction (DSRE) has been widely used, aiming to utilize knowledge base to automatically
  annotate datasets. Unfortunately, this method heavily suffers from wrong labelling
  due to its underlying strong assumptions. To address this issue, we propose a new
  framework using hybrid attention-based Transformer block with multi-instance learning
  for DSRE. More specifically, the Transformer block is, for the first time, used
  as a sentence encoder, which mainly utilizes multi-head self-attention to capture
  syntactic information at the word level. Then, a novel sentence-level attention
  mechanism is proposed to calculate the bag representation, aiming to exploit all
  useful information in each sentence. Experimental results on the public dataset
  New York Times (NYT) demonstrate that the proposed approach can outperform the state-of-the-art
  algorithms on the adopted dataset, which verifies the effectiveness of our model
  on the DSRE task.
publication: '*Neurocomputing*'
url_pdf: https://www.sciencedirect.com/science/article/pii/S0925231221015174
doi: 10.1016/j.neucom.2021.10.037
---
