---
layout: post
title: "Training Quantized Nets: A Deeper Understanding"
date: 2017-11-13 16:32:39
categories: arXiv_CV
tags: arXiv_CV Inference
author: Hao Li, Soham De, Zheng Xu, Christoph Studer, Hanan Samet, Tom Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, deep neural networks are deployed on low-power portable devices by first training a full-precision model using powerful hardware, and then deriving a corresponding low-precision model for efficient inference on such systems. However, training models directly with coarsely quantized weights is a key step towards learning on embedded platforms that have limited computing resources, memory capacity, and power consumption. Numerous recent publications have studied methods for training quantized networks, but these studies have mostly been empirical. In this work, we investigate training methods for quantized neural networks from a theoretical viewpoint. We first explore accuracy guarantees for training methods under convexity assumptions. We then look at the behavior of these algorithms for non-convex problems, and show that training algorithms that exploit high-precision representations have an important greedy search phase that purely quantized training methods lack, which explains the difficulty of training using low-precision arithmetic.

##### Abstract (translated by Google)
目前，深度神经网络部署在低功耗便携式设备上，首先利用强大的硬件对全精度模型进行训练，然后推导出相应的低精度模型，以便对这些系统进行高效推理。然而，直接使用粗量化权重的训练模型是在计算资源，内存容量和功耗有限的嵌入式平台上学习的关键一步。许多最近的出版物已经研究了量化网络的训练方法，但是这些研究主要是经验性的。在这项工作中，我们从理论的角度来研究量化的神经网络的训练方法。我们首先探讨在凸性假设下训练方法的精度保证。然后，我们看看这些算法对于非凸问题的行为，并且显示利用高精度表示的训练算法具有纯粹量化的训练方法缺乏的重要的贪婪搜索阶段，这解释了使用低精度算法。

##### URL
[https://arxiv.org/abs/1706.02379](https://arxiv.org/abs/1706.02379)

##### PDF
[https://arxiv.org/pdf/1706.02379](https://arxiv.org/pdf/1706.02379)

