---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A social learning particle swarm optimization algorithm for scalable optimization
subtitle: ''
summary: ''
authors:
- Ran Cheng
- Yaochu Jin
tags:
- '"Particle swarm optimization"'
- '"Large-scale optimization"'
- '"Scalability"'
- '"Computational efficiency"'
- '"Social learning"'
categories: []
date: '2015-01-01'
lastmod: 2021-08-27T07:59:43+08:00
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
publishDate: '2021-08-27T01:55:18.703368Z'
publication_types:
- '2'
abstract: Social learning plays an important role in behavior learning among social
  animals. In contrast to individual (asocial) learning, social learning has the advantage
  of allowing individuals to learn behaviors from others without incurring the costs
  of individual trials-and-errors. This paper introduces social learning mechanisms
  into particle swarm optimization (PSO) to develop a social learning PSO (SL-PSO).
  Unlike classical PSO variants where the particles are updated based on historical
  information, including the best solution found by the whole swarm (global best)
  and the best solution found by each particle (personal best), each particle in the
  proposed SL-PSO learns from any better particles (termed demonstrators) in the current
  swarm. In addition, to ease the burden of parameter settings, the proposed SL-PSO
  adopts a dimension-dependent parameter control method. The proposed SL-PSO is first
  compared with five representative PSO variants on 40 low-dimensional test functions,
  including shifted and rotated test functions. The scalability of the proposed SL-PSO
  is further tested by comparing it with five state-of-the-art algorithms for large-scale
  optimization on seven high-dimensional (100-D, 500-D, and 1000-D) benchmark functions.
  Our comparative results show that SL-PSO performs well on low-dimensional problems
  and is promising for solving large-scale problems as well.
publication: '*Information Sciences*'
url_pdf: https://www.sciencedirect.com/science/article/pii/S0020025514008366
doi: 10.1016/j.ins.2014.08.039
---
