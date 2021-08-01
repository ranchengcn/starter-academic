---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Multiobjective Evolutionary Algorithm Using Gaussian Process-Based Inverse
  Modeling
subtitle: ''
summary: ''
authors:
- Ran Cheng
- Yaochu Jin
- Kaname Narukawa
- Bernhard Sendhoff
tags:
- '"estimation of distribution algorithms"'
- '"Estimation of distribution algorithms (EDAs)"'
- '"Gaussian processes"'
- '"Gaussian processes (GPs)"'
- '"inverse modeling"'
- '"Inverse problems"'
- '"Multiobjective optimization"'
- '"multiobjective optimization (MOO)"'
- '"Pareto optimization"'
- '"random grouping"'
- '"Sociology"'
- '"Vectors"'
categories: []
date: '2015-12-01'
lastmod: 2021-08-01T21:34:52+08:00
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
publishDate: '2021-08-01T13:36:56.189011Z'
publication_types:
- '2'
abstract: To approximate the Pareto front, most existing multiobjective evolutionary
  algorithms store the nondominated solutions found so far in the population or in
  an external archive during the search. Such algorithms often require a high degree
  of diversity of the stored solutions and only a limited number of solutions can
  be achieved. By contrast, model-based algorithms can alleviate the requirement on
  solution diversity and in principle, as many solutions as needed can be generated.
  This paper proposes a new model-based method for representing and searching nondominated
  solutions. The main idea is to construct Gaussian process-based inverse models that
  map all found nondominated solutions from the objective space to the decision space.
  These inverse models are then used to create offspring by sampling the objective
  space. To facilitate inverse modeling, the multivariate inverse function is decomposed
  into a group of univariate functions, where the number of inverse models is reduced
  using a random grouping technique. Extensive empirical simulations demonstrate that
  the proposed algorithm exhibits robust search performance on a variety of medium
  to high dimensional multiobjective optimization test problems. Additional nondominated
  solutions are generated a posteriori using the constructed models to increase the
  density of solutions in the preferred regions at a low computational cost.
publication: '*IEEE Transactions on Evolutionary Computation*'
doi: 10.1109/TEVC.2015.2395073
---
