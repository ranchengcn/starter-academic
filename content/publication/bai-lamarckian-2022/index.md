---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Lamarckian Platform: Pushing the Boundaries of Evolutionary Reinforcement
  Learning Towards Asynchronous Commercial Games'
subtitle: ''
summary: ''
authors:
- Hui Bai
- Ruimin Shen
- Yue Lin
- Botian Xu
- Ran Cheng
tags:
- Artificial intelligence
- Asynchronous commercial games
- Benchmark testing
- evolutionary computation
- evolutionary reinforcement learning
- Games
- platform
- reinforcement learning
- Reinforcement learning
- Sociology
- Statistics
- Training
categories: []
date: '2022-01-01'
lastmod: 2023-03-16T12:30:51+08:00
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
publishDate: '2023-03-16T04:30:51.421061Z'
publication_types:
- '2'
abstract: 'Despite the emerging progress of integrating evolutionary computation into
  reinforcement learning, the absence of a high-performance platform endowing composability
  and massive parallelism causes non-trivial difficulties for research and applications
  related to asynchronous commercial games. Here we introduce Lamarckian11The code
  and demonstrational setup of Lamarckian are publicly available at https://github.
  com/lamarckian/lamarckian. – an open-source platform featuring support for evolutionary
  reinforcement learning scalable to distributed computing resources. To improve the
  training speed and data efficiency, Lamarckian adopts optimized communication methods
  and an asynchronous evolutionary reinforcement learning workflow. To meet the demand
  for an asynchronous interface by commercial games and various methods, Lamarckian
  tailors an asynchronous Markov Decision Process interface and designs an object-oriented
  software architecture with decoupled modules. In comparison with the state-of-the-art
  RLlib, we empirically demonstrate the unique advantages of Lamarckian on benchmark
  tests with up to 6000 CPU cores: i) both the sampling efficiency and training speed
  are doubled when running PPO on Google football game; ii) the training speed is
  13 times faster when running PBT+PPO on Pong game. Moreover, we also present two
  use cases: i) how Lamarckian is applied to generating behavior-diverse game AI;
  ii) how Lamarckian is applied to game balancing tests for an asynchronous commercial
  game.'
publication: '*IEEE Transactions on Games*'
doi: 10.1109/TG.2022.3208324
---
