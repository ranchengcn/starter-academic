---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SoloGAN: Multi-domain Multimodal Unpaired Image-to-Image Translation via a
  Single Generative Adversarial Network'
subtitle: ''
summary: ''
authors:
- Shihua Huang
- Cheng He
- Ran Cheng
tags:
- Generative adversarial network (GAN)
- Generative adversarial networks
- image synthesis
- Image synthesis
- image-to-image (I2I) translation
categories: []
date: '2022-10-01'
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
publishDate: '2023-03-16T04:30:50.785542Z'
publication_types:
- '2'
abstract: Despite significant advances in image-to-image (I2I) translation with generative
  adversarial networks (GANs), it remains challenging to effectively translate an
  image to a set of diverse images in multiple target domains using a pair of generator
  and discriminator. Existing multimodal I2I translation methods adopt multiple domain-specific
  content encoders for different domains, where each domain-specific content encoder
  is trained with images from the same domain only. Nevertheless, we argue that the
  content (domain-invariance) features should be learned from images among all of
  the domains. Consequently, each domain-specific content encoder of existing schemes
  fails to extract the domain-invariant features efficiently. To address this issue,
  we present a flexible and general SoloGAN model for efficient multimodal I2I translation
  among multiple domains with unpaired data. In contrast to existing methods, the
  SoloGAN algorithm uses a single projection discriminator with an additional auxiliary
  classifier and shares the encoder and generator for all domains. As such, the SoloGAN
  model can be trained effectively with images from all domains so that the domain-invariance
  content representation can be efficiently extracted. Qualitative and quantitative
  results over a wide range of datasets against several counterparts and variants
  of the SoloGAN model demonstrate the merits of the method, especially for challenging
  I2I translation tasks, i.e., tasks that involve extreme shape variations or need
  to keep the complex backgrounds unchanged after translations. Furthermore, we demonstrate
  the contribution of each component using ablation studies.
publication: '*IEEE Transactions on Artificial Intelligence*'
doi: 10.1109/TAI.2022.3187384
---
