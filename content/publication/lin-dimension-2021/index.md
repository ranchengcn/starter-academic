---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dimension Dropout for Evolutionary High-Dimensional Expensive Multiobjective
  Optimization
subtitle: ''
summary: ''
authors:
- Jianqing Lin
- Cheng He
- Ran Cheng
tags:
- '"Multiobjective optimization"'
- '"Dimension dropout"'
- '"High-dimensional"'
- '"Surrogate-assisted optimization"'
categories: []
date: '2021-01-01'
lastmod: 2021-08-27T07:59:33+08:00
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
publishDate: '2021-08-27T06:00:32.492008Z'
publication_types:
- '1'
abstract: In the past decades, a number of surrogate-assisted evolutionary algorithms
  (SAEAs) have been developed to solve expensive multiobjective optimization problems
  (EMOPs). However, most existing SAEAs focus on low-dimensional optimization problems,
  since a large number of training samples are required (which is unrealistic for
  EMOPs) to build an accurate surrogate model for high-dimensional problems. In this
  paper, an SAEA with Dimension Dropout is proposed to solve high-dimensional EMOPs.
  At each iteration of the proposed algorithm, it randomly selects a part of the decision
  variables by Dimension Dropout, and then optimizes the selected decision variables
  with the assistance of surrogate models. To balance the convergence and diversity,
  those candidate solutions with good diversity are modified by replacing the selected
  decision variables with those optimized ones (i.e., decision variables from some
  better-converged candidate solutions). Eventually, the new candidate solutions are
  evaluated using expensive functions to update the archive. Empirical studies on
  ten benchmark problems with up to 200 decision variables demonstrate the competitiveness
  of the proposed algorithm.
publication: '*Evolutionary Multi-Criterion Optimization*'
doi: 10.1007/978-3-030-72062-9_45
---
