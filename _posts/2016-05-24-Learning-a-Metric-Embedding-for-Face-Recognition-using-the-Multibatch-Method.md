---
layout: post
title: "Learning a Metric Embedding for Face Recognition using the Multibatch Method"
date: 2016-05-24 02:42:53
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN Prediction Gradient_Descent Recognition Face_Recognition
author: Oren Tadmor, Yonatan Wexler, Tal Rosenwein, Shai Shalev-Shwartz, Amnon Shashua
mathjax: true
---

* content
{:toc}

##### Abstract
This work is motivated by the engineering task of achieving a near state-of-the-art face recognition on a minimal computing budget running on an embedded system. Our main technical contribution centers around a novel training method, called Multibatch, for similarity learning, i.e., for the task of generating an invariant "face signature" through training pairs of "same" and "not-same" face images. The Multibatch method first generates signatures for a mini-batch of $k$ face images and then constructs an unbiased estimate of the full gradient by relying on all $k^2-k$ pairs from the mini-batch. We prove that the variance of the Multibatch estimator is bounded by $O(1/k^2)$, under some mild conditions. In contrast, the standard gradient estimator that relies on random $k/2$ pairs has a variance of order $1/k$. The smaller variance of the Multibatch estimator significantly speeds up the convergence rate of stochastic gradient descent. Using the Multibatch method we train a deep convolutional neural network that achieves an accuracy of $98.2\%$ on the LFW benchmark, while its prediction runtime takes only $30$msec on a single ARM Cortex A9 core. Furthermore, the entire training process took only 12 hours on a single Titan X GPU.

##### Abstract (translated by Google)
这项工作的动机是通过在嵌入式系统上运行最小的计算预算来实现接近最先进的人脸识别的工程任务。我们的主要技术贡献围绕一种称为Multibatch的新型训练方法来进行相似性学习，即通过训练“相同”和“不同”人脸图像对来生成不变的“人脸签名”。 Multibatch方法首先生成小批量$ k $人脸图像的签名，然后通过依赖小批量中的所有$ k ^ 2-k $对构建完整梯度的无偏估计。我们证明了在一些温和的条件下，Multibatch估计量的方差为$ O（1 / k ^ 2）$。相比之下，依赖于随机$ k / 2 $对的标准梯度估计量具有$ 1 / k $阶的方差。 Multibatch估计量的方差越小，随机梯度下降的收敛速度越快。使用Multibatch方法，我们训练了一个深度卷积神经网络，LFW基准测试的准确度为$ 98.2 \％$，而其预测运行时间在单个ARM Cortex A9内核上仅为$ 30 $ msec。而且，整个训练过程在单个Titan X GPU上只花费了12个小时。

##### URL
[https://arxiv.org/abs/1605.07270](https://arxiv.org/abs/1605.07270)

##### PDF
[https://arxiv.org/pdf/1605.07270](https://arxiv.org/pdf/1605.07270)

