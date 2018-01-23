---
layout: post
title: "Bayesian Deep Convolutional Encoder-Decoder Networks for Surrogate Modeling and Uncertainty Quantification"
date: 2018-01-21 19:18:13
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning Gradient_Descent
author: Yinhao Zhu, Nicholas Zabaras
mathjax: true
---

* content
{:toc}

##### Abstract
We are interested in the development of surrogate models for uncertainty quantification and propagation in problems governed by stochastic PDEs using a deep convolutional encoder-decoder network in a similar fashion to approaches considered in deep learning for image-to-image regression tasks. Since normal neural networks are data intensive and cannot provide predictive uncertainty, we propose a Bayesian approach to convolutional neural nets. A recently introduced variational gradient descent algorithm based on Stein's method is scaled to deep convolutional networks to perform approximate Bayesian inference on millions of uncertain network parameters. This approach achieves state of the art performance in terms of predictive accuracy and uncertainty quantification in comparison to other approaches in Bayesian neural networks as well as techniques that include Gaussian processes and ensemble methods even when the training data size is relatively small. To evaluate the performance of this approach, we consider standard uncertainty quantification benchmark problems including flow in heterogeneous media defined in terms of limited data-driven permeability realizations. The performance of the surrogate model developed is very good even though there is no underlying structure shared between the input (permeability) and output (flow/pressure) fields as is often the case in the image-to-image regression models used in computer vision problems. Studies are performed with an underlying stochastic input dimensionality up to $4,225$ where most other uncertainty quantification methods fail. Uncertainty propagation tasks are considered and the predictive output Bayesian statistics are compared to those obtained with Monte Carlo estimates.

##### Abstract (translated by Google)
我们感兴趣的是在深度卷积编码器 - 解码器网络中使用深度卷积编码器 - 解码器网络以与在深度学习中考虑用于图像 - 图像回归任务的方法一起在由随机PDE控制的问题中发展不确定度量化和传播的替代模型。由于正常的神经网络数据密集，不能提供预测的不确定性，我们提出了一个贝叶斯方法的卷积神经网络。最近引入的基于Stein方法的变分梯度下降算法被缩放到深度卷积网络，以对数百万个不确定的网络参数执行近似的贝叶斯推断。与贝叶斯神经网络中的其他方法以及包括高斯过程和集成方法的技术相比，即使在训练数据量相对较小的情况下，该方法在预测准确性和不确定性量化方面实现了最新的性能。为了评估这种方法的性能，我们考虑标准不确定性量化基准问题，包括在有限数据驱动的渗透率实现方面定义的异构介质中的流量。即使在输入（渗透率）和输出（流量/压力）场之间没有共享的底层结构，开发的替代模型的性能是非常好的，这在计算机视觉中使用的图像到图像回归模型中经常是这种情况问题。研究的底层随机输入维度高达$ 4,225 $，其中大多数其他不确定性量化方法失败。考虑不确定性传播任务，并将预测输出贝叶斯统计与蒙特卡罗估计得到的结果进行比较。

##### URL
[https://arxiv.org/abs/1801.06879](https://arxiv.org/abs/1801.06879)

##### PDF
[https://arxiv.org/pdf/1801.06879](https://arxiv.org/pdf/1801.06879)

