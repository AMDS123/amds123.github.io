---
layout: post
title: "Profile-guided memory optimization for deep neural networks"
date: 2018-04-26 11:42:39
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Taro Sekiyama, Takashi Imamichi, Haruki Imai, Rudy Raymond
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen deep neural networks (DNNs) becoming wider and deeper to achieve better performance in many applications of AI. Such DNNs however require huge amounts of memory to store weights and intermediate results (e.g., activations, feature maps, etc.) in propagation. This requirement makes it difficult to run the DNNs on devices with limited, hard-to-extend memory, degrades the running time performance, and restricts the design of network models. We address this challenge by developing a novel profile-guided memory optimization to efficiently and quickly allocate memory blocks during the propagation in DNNs. The optimization utilizes a simple and fast heuristic algorithm based on the two-dimensional rectangle packing problem. Experimenting with well-known neural network models, we confirm that our method not only reduces the memory consumption by up to $49.5\%$ but also accelerates training and inference by up to a factor of four thanks to the rapidity of the memory allocation and the ability to use larger mini-batch sizes.

##### Abstract (translated by Google)
近年来，深层神经网络（DNN）越来越广泛和深入，以在AI的许多应用中实现更好的性能。然而，这样的DNN需要大量的存储器来存储传播中的权重和中间结果（例如激活，特征映射等）。该要求使得难以在具有有限的难以扩展的存储器的设备上运行DNN，降低了运行时间性能并限制了网络模型的设计。我们通过开发一种新颖的配置文件指导内存优化来解决这一难题，以便在DNN传播过程中高效快速地分配内存块。该优化利用基于二维矩形填充问题的简单而快速的启发式算法。试验着名的神经网络模型，我们确认我们的方法不仅可以减少高达49.5％的内存消耗，而且由于内存分配的快速性以及能够使用更大的小批量尺寸。

##### URL
[https://arxiv.org/abs/1804.10001](https://arxiv.org/abs/1804.10001)

##### PDF
[https://arxiv.org/pdf/1804.10001](https://arxiv.org/pdf/1804.10001)

