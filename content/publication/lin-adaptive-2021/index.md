---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adaptive dropout for high-dimensional expensive multiobjective optimization
subtitle: ''
summary: ''
authors:
- Jianqing Lin
- Cheng He
- Ran Cheng
tags: []
categories: []
date: '2021-04-01'
lastmod: 2021-08-27T07:59:35+08:00
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
publishDate: '2021-08-27T01:42:22.747612Z'
publication_types:
- '2'
abstract: Various works have been proposed to solve expensive multiobjective optimization
  problems (EMOPs) using surrogate-assisted evolutionary algorithms (SAEAs) in recent
  decades. However, most existing methods focus on EMOPs with less than 30 decision
  variables, since a large number of training samples are required to build an accurate
  surrogate model for high-dimensional EMOPs, which is unrealistic for expensive multiobjective
  optimization. To address this issue, we propose an SAEA with an adaptive dropout
  mechanism. Specifically, this mechanism takes advantage of the statistical differences
  between different solution sets in the decision space to guide the selection of
  some crucial decision variables. A new infill criterion is then proposed to optimize
  the selected decision variables with the assistance of surrogate models. Moreover,
  the optimized decision variables are extended to new full-length solutions, and
  then the new candidate solutions are evaluated using expensive functions to update
  the archive. The proposed algorithm is tested on different benchmark problems with
  up to 200 decision variables compared to some state-of-the-art SAEAs. The experimental
  results have demonstrated the promising performance and computational efficiency
  of the proposed algorithm in high-dimensional expensive multiobjective optimization.
publication: '*Complex & Intelligent Systems*'
url_pdf: https://doi.org/10.1007/s40747-021-00362-5
doi: 10.1007/s40747-021-00362-5
---
