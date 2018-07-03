---
layout: post
title: "SYQ: Learning Symmetric Quantization For Efficient Deep Neural Networks"
date: 2018-07-01 09:29:19
categories: arXiv_CV
tags: arXiv_CV Inference
author: Julian Faraone, Nicholas Fraser, Michaela Blott, Philip H.W. Leong
mathjax: true
---

* content
{:toc}

##### Abstract
Inference for state-of-the-art deep neural networks is computationally expensive, making them difficult to deploy on constrained hardware environments. An efficient way to reduce this complexity is to quantize the weight parameters and/or activations during training by approximating their distributions with a limited entry codebook. For very low-precisions, such as binary or ternary networks with 1-8-bit activations, the information loss from quantization leads to significant accuracy degradation due to large gradient mismatches between the forward and backward functions. In this paper, we introduce a quantization method to reduce this loss by learning a symmetric codebook for particular weight subgroups. These subgroups are determined based on their locality in the weight matrix, such that the hardware simplicity of the low-precision representations is preserved. Empirically, we show that symmetric quantization can substantially improve accuracy for networks with extremely low-precision weights and activations. We also demonstrate that this representation imposes minimal or no hardware implications to more coarse-grained approaches. Source code is available at https://www.github.com/julianfaraone/SYQ.

##### Abstract (translated by Google)
对最先进的深度神经网络的推断在计算上是昂贵的，使得它们难以在受约束的硬件环境上部署。减少这种复杂性的有效方法是通过用有限的入口码本来近似他们的分布来量化训练期间的权重参数和/或激活。对于非常低的精度，例如具有1-8位激活的二进制或三进制网络，由于前向和后向功能之间的大的梯度失配，来自量化的信息损失导致显着的精度降级。在本文中，我们引入量化方法来通过学习特定权重子群的对称码本来减少这种损失。这些子群是根据它们在权重矩阵中的局部性来确定的，从而保留了低精度表示的硬件简单性。根据经验，我们证明了对称量化可以显着提高具有极低精度权重和激活的网络的准确性。我们还证明，这种表示对更粗粒度的方法施加的硬件影响很小或没有影响。源代码可在https://www.github.com/julianfaraone/SYQ获得。

##### URL
[http://arxiv.org/abs/1807.00301](http://arxiv.org/abs/1807.00301)

##### PDF
[http://arxiv.org/pdf/1807.00301](http://arxiv.org/pdf/1807.00301)

