---
# Documentation: https://wowchemy.com/docs/managing-content/

title: End-to-End Dense Video Captioning with Parallel Decoding
subtitle: ''
summary: ''
authors:
- Teng Wang
- Ruimao Zhang
- Zhichao Lu
- Feng Zheng
- Ran Cheng
- Ping Luo
tags:
- '"Computer Science - Computer Vision and Pattern Recognition"'
- '"68T45"'
- '"I.4.9"'
- '"I.5.4"'
categories: []
date: '2021-08-01'
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
publishDate: '2021-08-27T06:00:43.956316Z'
publication_types:
- '2'
abstract: 'Dense video captioning aims to generate multiple associated captions with
  their temporal locations from the video. Previous methods follow a sophisticated
  \"localize-then-describe\" scheme, which heavily relies on numerous hand-crafted
  components. In this paper, we proposed a simple yet effective framework for end-to-end
  dense video captioning with parallel decoding (PDVC), by formulating the dense caption
  generation as a set prediction task. In practice, through stacking a newly proposed
  event counter on the top of a transformer decoder, the PDVC precisely segments the
  video into a number of event pieces under the holistic understanding of the video
  content, which effectively increases the coherence and readability of predicted
  captions. Compared with prior arts, the PDVC has several appealing advantages: (1)
  Without relying on heuristic non-maximum suppression or a recurrent event sequence
  selection network to remove redundancy, PDVC directly produces an event set with
  an appropriate size; (2) In contrast to adopting the two-stage scheme, we feed the
  enhanced representations of event queries into the localization head and caption
  head in parallel, making these two sub-tasks deeply interrelated and mutually promoted
  through the optimization; (3) Without bells and whistles, extensive experiments
  on ActivityNet Captions and YouCook2 show that PDVC is capable of producing high-quality
  captioning results, surpassing the state-of-the-art two-stage methods when its localization
  accuracy is on par with them. Code is available at https://github.com/ttengwang/PDVC.'
publication: '*arXiv:2108.07781 [cs]*'
url_pdf: http://arxiv.org/abs/2108.07781
---
