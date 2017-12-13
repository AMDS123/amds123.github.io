---
layout: post
title: "Parameter Compression of Recurrent Neural Networks and Degradation of Short-term Memory"
date: 2017-02-24 18:22:30
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Jonathan A. Cox
mathjax: true
---

* content
{:toc}

##### Abstract
The significant computational costs of deploying neural networks in large-scale or resource constrained environments, such as data centers and mobile devices, has spurred interest in model compression, which can achieve a reduction in both arithmetic operations and storage memory. Several techniques have been proposed for reducing or compressing the parameters for feed-forward and convolutional neural networks, but less is understood about the effect of parameter compression on recurrent neural networks (RNN). In particular, the extent to which the recurrent parameters can be compressed and the impact on short-term memory performance, is not well understood. In this paper, we study the effect of complexity reduction, through singular value decomposition rank reduction, on RNN and minimal gated recurrent unit (MGRU) networks for several tasks. We show that considerable rank reduction is possible when compressing recurrent weights, even without fine tuning. Furthermore, we propose a perturbation model for the effect of general perturbations, such as a compression, on the recurrent parameters of RNNs. The model is tested against a noiseless memorization experiment that elucidates the short-term memory performance. In this way, we demonstrate that the effect of compression of recurrent parameters is dependent on the degree of temporal coherence present in the data and task. This work can guide on-the-fly RNN compression for novel environments or tasks, and provides insight for applying RNN compression in low-power devices, such as hearing aids.

##### Abstract (translated by Google)
在数据中心和移动设备等大规模或资源受限的环境中部署神经网络的重大计算成本激发了对模型压缩的兴趣，这可以减少算术运算和存储内存。已经提出了几种用于减少或压缩前馈和卷积神经网络参数的技术，但是关于参数压缩对递归神经网络（RNN）的影响的了解较少。尤其是，复发参数可以被压缩的程度以及对短期记忆性能的影响，还不是很清楚。在本文中，我们研究了通过奇异值分解等级降低的复杂度降低对RNN和最小门控循环单元（MGRU）网络的几个任务的影响。我们表明，即使没有进行微调，在压缩周期性重量时也可能有相当的等级降低。此外，我们提出了一个摄动模型，用来研究一般摄动（如压缩）对RNNs的递归参数的影响。该模型是针对无声的记忆实验进行测试的，该实验阐明了短时记忆的表现。这样，我们证明了经常性参数压缩的效果取决于数据和任务中存在的时间一致性程度。这项工作可以为新颖的环境或任务指导实时的RNN压缩，并提供在低功率设备（如助听器）中应用RNN压缩的见解。

##### URL
[https://arxiv.org/abs/1612.00891](https://arxiv.org/abs/1612.00891)

##### PDF
[https://arxiv.org/pdf/1612.00891](https://arxiv.org/pdf/1612.00891)

