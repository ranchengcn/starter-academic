---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adaptive Control of Subpopulations in Evolutionary Dynamic Optimization
subtitle: ''
summary: ''
authors:
- Danial Yazdani
- Ran Cheng
- Cheng He
- Jürgen Branke
tags:
- Sociology
- Statistics
- multipopulation
- Resource management
- dynamic optimization problems (DOPs)
- Computational resource allocation
- Euclidean distance
- Round robin
- Tracking
- tracking moving optima (TMO)
- Upper bound
categories: []
date: '2020-01-01'
lastmod: 2023-03-16T12:30:40+08:00
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
publishDate: '2023-03-16T04:30:39.893348Z'
publication_types:
- '2'
abstract: 'Multipopulation methods are highly effective in solving dynamic optimization
  problems. Three factors affect this significantly: 1) the exclusion mechanisms to
  avoid the convergence to the same peak by multiple subpopulations; 2) the resource
  allocation mechanism that assigns the computational resources to the subpopulations;
  and 3) the control mechanisms to adaptively adjust the number of subpopulations
  by considering the number of optima and available computational resources. In the
  existing exclusion mechanisms, when the distance (i.e., the distance between their
  best found positions) between two subpopulations becomes less than a predefined
  threshold, the inferior one will be removed/reinitialized. However, this leads to
  incapability of algorithms in covering peaks/optima that are closer than the threshold.
  Moreover, despite the importance of resource allocation due to the limited available
  computational resources between environmental changes, it has not been well studied
  in the literature. Finally, the number of subpopulations should be adapted to the
  number of optima. However, in most existing adaptive multipopulation methods, there
  is no predefined upper bound for generating subpopulations. Consequently, in problems
  with large numbers of peaks, they can generate too many subpopulations sharing limited
  computational resources. In this article, a multipopulation framework is proposed
  to address the aforementioned issues by using three adaptive approaches: 1) subpopulation
  generation; 2) double-layer exclusion; and 3) computational resource allocation.
  The experimental results demonstrate the superiority of the proposed framework over
  several peer approaches in solving various benchmark problems.'
publication: '*IEEE Transactions on Cybernetics*'
doi: 10.1109/TCYB.2020.3036100
---
