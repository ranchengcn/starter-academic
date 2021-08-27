---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient evolutionary neural architecture search by modular inheritable crossover
subtitle: ''
summary: ''
authors:
- Cheng He
- Hao Tan
- Shihua Huang
- Ran Cheng
tags:
- '"Evolutionary algorithm"'
- '"Image classification"'
- '"Inheritable crossover"'
- '"Neural architecture search"'
categories: []
date: '2021-07-01'
lastmod: 2021-08-27T08:43:05+08:00
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
publishDate: '2021-08-27T01:55:21.096851Z'
publication_types:
- '2'
abstract: Deep neural networks are widely used in the domain of image classification,
  and a large number of excellent deep neural networks have been proposed in recent
  years. However, hand-crafted neural networks often require human experts for elaborate
  designs, which can be time-consuming and error-prone. Hence, neural architecture
  search (NAS) methods have been proposed to design model architecture automatically.
  The evolutionary NAS methods have achieved encouraging results due to the global
  search capability of evolutionary algorithms. Nevertheless, most existing evolutionary
  NAS methods use only the mutation operator to generate offspring architectures.
  Consequently, the generated architectures could be pretty different from their parent
  architectures, failing to inherit the modular information to accelerate the convergence
  rate. We propose an efficient evolutionary method using a tailored crossover operator
  to address this deficiency, which enables the offspring architectures to inherit
  from their parent architectures. Moreover, we combine it with mutation operators
  under the framework of the evolutionary algorithm. Experimental results on both
  the CIFAR-10 and CIFAR-100 tasks show that our proposed evolutionary NAS method
  has achieved state-of-the-art results.
publication: '*Swarm and Evolutionary Computation*'
url_pdf: https://www.sciencedirect.com/science/article/pii/S2210650221000559
doi: 10.1016/j.swevo.2021.100894
---
