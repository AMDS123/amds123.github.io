---
layout: post
title: "Embedded Binarized Neural Networks"
date: 2017-09-06 06:45:33
categories: arXiv_CV
tags: arXiv_CV Inference
author: Bradley McDanel, Surat Teerapittayanon, H.T. Kung
mathjax: true
---

* content
{:toc}

##### Abstract
We study embedded Binarized Neural Networks (eBNNs) with the aim of allowing current binarized neural networks (BNNs) in the literature to perform feedforward inference efficiently on small embedded devices. We focus on minimizing the required memory footprint, given that these devices often have memory as small as tens of kilobytes (KB). Beyond minimizing the memory required to store weights, as in a BNN, we show that it is essential to minimize the memory used for temporaries which hold intermediate results between layers in feedforward inference. To accomplish this, eBNN reorders the computation of inference while preserving the original BNN structure, and uses just a single floating-point temporary for the entire neural network. All intermediate results from a layer are stored as binary values, as opposed to floating-points used in current BNN implementations, leading to a 32x reduction in required temporary space. We provide empirical evidence that our proposed eBNN approach allows efficient inference (10s of ms) on devices with severely limited memory (10s of KB). For example, eBNN achieves 95\% accuracy on the MNIST dataset running on an Intel Curie with only 15 KB of usable memory with an inference runtime of under 50 ms per sample. To ease the development of applications in embedded contexts, we make our source code available that allows users to train and discover eBNN models for a learning task at hand, which fit within the memory constraint of the target device.

##### Abstract (translated by Google)
我们研究嵌入式二值化神经网络（eBNNs），目的在于允许文献中的当前二值化神经网络（BNN）在小型嵌入式设备上有效地执行前馈推理。考虑到这些设备通常具有几十千字节（KB）的内存，我们专注于最小化所需的内存占用。除了最小化存储权重所需的内存（如BNN）之外，我们还表明，在前馈推理中最小化用于临时存储中间结果的内存是非常重要的。为了达到这个目的，eBNN在保留原始BNN结构的同时对推理计算进行重新排序，并且对整个神经网络仅使用单个浮点临时值。来自一个图层的所有中间结果都以二进制值的形式存储，而不是当前BNN实现中使用的浮点数，导致所需临时空间减少了32倍。我们提供的经验证据表明，我们提出的eBNN方法可以在内存严重有限（10s的KB）的设备上进行有效的推断（10ms）。例如，eBNN在英特尔居里上运行的MNIST数据集上的准确度达到95％，只有15 KB的可用内存，每个样本的推理运行时间低于50 ms。为了简化应用程序在嵌入式环境中的开发，我们使我们的源代码可用，允许用户训练和发现eBNN模型，以完成手头的学习任务，这些任务符合目标设备的内存限制。

##### URL
[https://arxiv.org/abs/1709.02260](https://arxiv.org/abs/1709.02260)

##### PDF
[https://arxiv.org/pdf/1709.02260](https://arxiv.org/pdf/1709.02260)

