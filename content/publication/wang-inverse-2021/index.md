---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An inverse design method for supercritical airfoil based on conditional generative
  models
subtitle: ''
summary: ''
authors:
- Jing Wang
- Runze Li
- Cheng He
- Haixin Chen
- Ran Cheng
- Chen Zhai
- Miao Zhang
tags:
- '"Conditional Variational AutoEncoder (CVAE)"'
- '"Deep learning"'
- '"Generative Adversarial Networks (GAN)"'
- '"Generative models"'
- '"Inverse design"'
- '"Supercritical airfoil"'
categories: []
date: '2021-03-01'
lastmod: 2021-08-01T21:34:45+08:00
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
publishDate: '2021-08-01T13:36:47.988162Z'
publication_types:
- '2'
abstract: Inverse design has long been an efficient and powerful design tool in the
  aircraft industry. In this paper, a novel inverse design method for supercritical
  airfoils is proposed based on generative models in deep learning. A Conditional
  Variational AutoEncoder (CVAE) and an integrated generative network CVAE-GAN that
  combines the CVAE with the Wasserstein Generative Adversarial Networks (WGAN), are
  conducted as generative models. They are used to generate target wall Mach distributions
  for the inverse design that matches specified features, such as locations of suction
  peak, shock and aft loading. Qualitative and quantitative results show that both
  adopted generative models can generate diverse and realistic wall Mach number distributions
  satisfying the given features. The CVAE-GAN model outperforms the CVAE model and
  achieves better reconstruction accuracies for all the samples in the dataset. Furthermore,
  a deep neural network for nonlinear mapping is adopted to obtain the airfoil shape
  corresponding to the target wall Mach number distribution. The performances of the
  designed deep neural network are fully demonstrated and a smoothness measurement
  is proposed to quantify small oscillations in the airfoil surface, proving the authenticity
  and accuracy of the generated airfoil shapes.
publication: '*Chinese Journal of Aeronautics*'
url_pdf: https://www.sciencedirect.com/science/article/pii/S1000936121000662
doi: 10.1016/j.cja.2021.03.006
---
