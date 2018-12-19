---
layout: post
title: "Unsupervised Single Image Dehazing Using Dark Channel Prior Loss"
date: 2018-12-06 11:29:38
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Alona Golts, Daniel Freedman, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
Single image dehazing is a critical stage in many modern-day autonomous vision applications. Early prior-based methods often involved a time-consuming minimization of a hand-crafted energy function. Recent learning-based approaches utilize the representational power of deep neural networks (DNNs) to learn the underlying transformation between hazy and clear images. Due to inherent limitations in collecting matching clear and hazy images, these methods resort to training on synthetic data; constructed from indoor images and corresponding depth information. This may result in a possible domain shift when treating outdoor scenes. We propose a completely unsupervised method of training via minimization of the well-known, Dark Channel Prior (DCP) energy function. Instead of feeding the network with synthetic data, we solely use real-world outdoor images and tune the network's parameters by directly minimizing the DCP. Although our `Deep DCP' technique can be regarded as a fast approximator of DCP, it actually improves its results significantly. This suggests an additional regularization obtained via the network and learning process. Experiments show that our method performs on par with other large-scale, supervised methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07051](http://arxiv.org/abs/1812.07051)

##### PDF
[http://arxiv.org/pdf/1812.07051](http://arxiv.org/pdf/1812.07051)

