---
layout: post
title: "Impostor Networks for Fast Fine-Grained Recognition"
date: 2018-06-13 18:44:10
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Vadim Lebedev, Artem Babenko, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce impostor networks, an architecture that allows to perform fine-grained recognition with high accuracy and using a light-weight convolutional network, making it particularly suitable for fine-grained applications on low-power and non-GPU enabled platforms. Impostor networks compensate for the lightness of its `backend' network by combining it with a lightweight non-parametric classifier. The combination of a convolutional network and such non-parametric classifier is trained in an end-to-end fashion. Similarly to convolutional neural networks, impostor networks can fit large-scale training datasets very well, while also being able to generalize to new data points. At the same time, the bulk of computations within impostor networks happen through nearest neighbor search in high-dimensions. Such search can be performed efficiently on a variety of architectures including standard CPUs, where deep convolutional networks are inefficient. In a series of experiments with three fine-grained datasets, we show that impostor networks are able to boost the classification accuracy of a moderate-sized convolutional network considerably at a very small computational cost.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.05217](https://arxiv.org/abs/1806.05217)

##### PDF
[https://arxiv.org/pdf/1806.05217](https://arxiv.org/pdf/1806.05217)

