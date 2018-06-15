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
在这项工作中，我们推出了骗子网络，这种架构允许以高精度执行细粒度识别并使用轻量级卷积网络，使其特别适用于低功耗和非GPU平台上的细粒度应用。冒充者网络通过将其与轻量级的非参数分类器相结合来弥补其“后端”网络的轻便性。卷积网络和这种非参数分类器的组合是以端到端的方式进行训练的。与卷积神经网络类似，冒充者网络可以很好地适应大规模训练数据集，同时还能够推广到新的数据点。同时，冒充者网络中的大量计算通过高维度上的最近邻居搜索而发生。这种搜索可以在包括标准CPU在内的各种体系结构上高效地执行，在这些体系结构中，深度卷积网络效率低下。在对三个细粒度数据集进行的一系列实验中，我们表明，冒充者网络能够以非常小的计算成本显着提高中等大小的卷积网络的分类准确性。

##### URL
[http://arxiv.org/abs/1806.05217](http://arxiv.org/abs/1806.05217)

##### PDF
[http://arxiv.org/pdf/1806.05217](http://arxiv.org/pdf/1806.05217)

