---
layout: post
title: "Predicting distributions with Linearizing Belief Networks"
date: 2016-05-02 03:22:01
categories: arXiv_CV
tags: arXiv_CV Face Optimization Prediction Gradient_Descent
author: Yann N. Dauphin, David Grangier
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional belief networks introduce stochastic binary variables in neural networks. Contrary to a classical neural network, a belief network can predict more than the expected value of the output $Y$ given the input $X$. It can predict a distribution of outputs $Y$ which is useful when an input can admit multiple outputs whose average is not necessarily a valid answer. Such networks are particularly relevant to inverse problems such as image prediction for denoising, or text to speech. However, traditional sigmoid belief networks are hard to train and are not suited to continuous problems. This work introduces a new family of networks called linearizing belief nets or LBNs. A LBN decomposes into a deep linear network where each linear unit can be turned on or off by non-deterministic binary latent units. It is a universal approximator of real-valued conditional distributions and can be trained using gradient descent. Moreover, the linear pathways efficiently propagate continuous information and they act as multiplicative skip-connections that help optimization by removing gradient diffusion. This yields a model which trains efficiently and improves the state-of-the-art on image denoising and facial expression generation with the Toronto faces dataset.

##### Abstract (translated by Google)
条件信念网络在神经网络中引入了随机二元变量。与经典的神经网络相反，信念网络可以预测超过给定$ X $的输出$ Y $的预期值。它可以预测输出的分布$ Y $，当输入可以录入多个输出时，这个输出的平均值不一定是有效答案。这样的网络特别与反向问题有关，例如用于去噪的图像预测或文本到语音。然而，传统的S形信念网络很难训练，不适合持续的问题。这项工作引入了一个称为线性化信念网络或LBNs的新的网络家族。一个LBN分解成一个深度线性网络，每个线性单元可以通过非确定性的二进制潜单元打开或关闭。它是实值条件分布的通用逼近器，可以使用梯度下降进行训练。此外，线性路径有效地传播连续的信息，并作为乘法跳跃连接，通过消除梯度扩散来帮助优化。这产生了一个模型，有效地训练，并改善与多伦多面孔数据集的图像去噪和面部表情生成的最新技术。

##### URL
[https://arxiv.org/abs/1511.05622](https://arxiv.org/abs/1511.05622)

##### PDF
[https://arxiv.org/pdf/1511.05622](https://arxiv.org/pdf/1511.05622)

