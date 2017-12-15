---
layout: post
title: "FractalNet: Ultra-Deep Neural Networks without Residuals"
date: 2017-05-26 18:53:56
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Classification
author: Gustav Larsson, Michael Maire, Gregory Shakhnarovich
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a design strategy for neural network macro-architecture based on self-similarity. Repeated application of a simple expansion rule generates deep networks whose structural layouts are precisely truncated fractals. These networks contain interacting subpaths of different lengths, but do not include any pass-through or residual connections; every internal signal is transformed by a filter and nonlinearity before being seen by subsequent layers. In experiments, fractal networks match the excellent performance of standard residual networks on both CIFAR and ImageNet classification tasks, thereby demonstrating that residual representations may not be fundamental to the success of extremely deep convolutional neural networks. Rather, the key may be the ability to transition, during training, from effectively shallow to deep. We note similarities with student-teacher behavior and develop drop-path, a natural extension of dropout, to regularize co-adaptation of subpaths in fractal architectures. Such regularization allows extraction of high-performance fixed-depth subnetworks. Additionally, fractal networks exhibit an anytime property: shallow subnetworks provide a quick answer, while deeper subnetworks, with higher latency, provide a more accurate answer.

##### Abstract (translated by Google)
我们介绍一种基于自相似性的神经网络宏观体系结构的设计策略。重复应用简单的扩展规则会生成深度网络，其结构布局是截断分形。这些网络包含不同长度的交互子路径，但不包括任何传递或剩余连接;每一个内部信号都被滤波器和非线性变换，然后被后续层看到。在实验中，分形网络与CIFAR和ImageNet分类任务中标准残差网络的优良性能相匹配，从而证明残差表示可能不是极深卷积神经网络成功的基础。相反，关键可能是在训练过程中，从浅到深的过渡能力。我们注意到与学生 - 教师行为的相似之处，并形成了辍学路径，这是辍学的自然延伸，以规范分形结构中的子路径的共同适应。这种正则化允许提取高性能的固定深度的子网络。此外，分形网络展现出随时随地的性质：浅层子网络提供了一个快速的答案，而更深的子网络具有更高的延迟，可以提供更准确的答案。

##### URL
[https://arxiv.org/abs/1605.07648](https://arxiv.org/abs/1605.07648)

##### PDF
[https://arxiv.org/pdf/1605.07648](https://arxiv.org/pdf/1605.07648)

