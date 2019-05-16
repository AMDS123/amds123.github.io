---
layout: post
title: "Stochastic Gradient Push for Distributed Deep Learning"
date: 2019-05-14 19:59:00
categories: arXiv_AI
tags: arXiv_AI Image_Classification Classification Deep_Learning
author: Mahmoud Assran, Nicolas Loizou, Nicolas Ballas, Michael Rabbat
mathjax: true
---

* content
{:toc}

##### Abstract
Distributed data-parallel algorithms aim to accelerate the training of deep neural networks by parallelizing the computation of large mini-batch gradient updates across multiple nodes. Approaches that synchronize nodes using exact distributed averaging (e.g., via AllReduce) are sensitive to stragglers and communication delays. The PushSum gossip algorithm is robust to these issues, but only performs approximate distributed averaging. This paper studies Stochastic Gradient Push (SGP), which combines PushSum with stochastic gradient updates. We prove that SGP converges to a stationary point of smooth, non-convex objectives at the same sub-linear rate as SGD, and that all nodes achieve consensus. We empirically validate the performance of SGP on image classification (ResNet-50, ImageNet) and machine translation (Transformer, WMT'16 En-De) workloads. Our code will be made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10792](http://arxiv.org/abs/1811.10792)

##### PDF
[http://arxiv.org/pdf/1811.10792](http://arxiv.org/pdf/1811.10792)

