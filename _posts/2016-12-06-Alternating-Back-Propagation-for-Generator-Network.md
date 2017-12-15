---
layout: post
title: "Alternating Back-Propagation for Generator Network"
date: 2016-12-06 04:04:19
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Tian Han, Yang Lu, Song-Chun Zhu, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an alternating back-propagation algorithm for learning the generator network model. The model is a non-linear generalization of factor analysis. In this model, the mapping from the continuous latent factors to the observed signal is parametrized by a convolutional neural network. The alternating back-propagation algorithm iterates the following two steps: (1) Inferential back-propagation, which infers the latent factors by Langevin dynamics or gradient descent. (2) Learning back-propagation, which updates the parameters given the inferred latent factors by gradient descent. The gradient computations in both steps are powered by back-propagation, and they share most of their code in common. We show that the alternating back-propagation algorithm can learn realistic generator models of natural images, video sequences, and sounds. Moreover, it can also be used to learn from incomplete or indirect training data.

##### Abstract (translated by Google)
本文提出了一种用于学习发电机网络模型的交替反向传播算法。该模型是因子分析的非线性泛化。在这个模型中，从连续潜伏因子到观测信号的映射是由卷积神经网络参数化的。交替的反向传播算法重复以下两个步骤：（1）推断向后传播，其通过朗之万动态或梯度下降来推断潜在因子。 （2）学习反向传播，其通过梯度下降更新给出推断的潜在因子的参数。两个步骤中的梯度计算都是由反向传播驱动的，它们共享大部分代码。我们表明，交替的反向传播算法可以学习自然图像，视频序列和声音的逼真的发生器模型。此外，它也可以用来从不完整或间接的培训数据中学习。

##### URL
[https://arxiv.org/abs/1606.08571](https://arxiv.org/abs/1606.08571)

##### PDF
[https://arxiv.org/pdf/1606.08571](https://arxiv.org/pdf/1606.08571)

