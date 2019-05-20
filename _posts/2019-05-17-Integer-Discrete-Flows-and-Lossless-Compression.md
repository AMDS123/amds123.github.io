---
layout: post
title: "Integer Discrete Flows and Lossless Compression"
date: 2019-05-17 17:07:58
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Emiel Hoogeboom, Jorn W.T. Peters, Rianne van den Berg, Max Welling
mathjax: true
---

* content
{:toc}

##### Abstract
Lossless compression methods shorten the expected representation size of data without loss of information, using a statistical model. Flow-based models are attractive in this setting because they admit exact likelihood optimization, which is equivalent to minimizing the expected number of bits per message. However, conventional flows assume continuous data, which may lead to reconstruction errors when quantized for compression. For that reason, we introduce a generative flow for ordinal discrete data called Integer Discrete Flow (IDF): a bijective integer map that can learn rich transformations on high-dimensional data. As building blocks for IDFs, we introduce flexible transformation layers called integer discrete coupling and lower triangular coupling. Our experiments show that IDFs are competitive with other flow-based generative models. Furthermore, we demonstrate that IDF based compression achieves state-of-the-art lossless compression rates on CIFAR10, ImageNet32, and ImageNet64.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07376](http://arxiv.org/abs/1905.07376)

##### PDF
[http://arxiv.org/pdf/1905.07376](http://arxiv.org/pdf/1905.07376)

