---
layout: post
title: "Deep Learning using Rectified Linear Units"
date: 2018-03-22 14:30:17
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Prediction
author: Abien Fred Agarap
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the use of rectified linear units (ReLU) as the classification function in a deep neural network (DNN). Conventionally, ReLU is used as an activation function in DNNs, with Softmax function as their classification function. However, there have been several studies on using a classification function other than Softmax, and this study is an addition to those. We accomplish this by taking the activation of the penultimate layer $h_{n - 1}$ in a neural network, then multiply it by weight parameters $\theta$ to get the raw scores $o_{i}$. Afterwards, we threshold the raw scores $o_{i}$ by $0$, i.e. $f(o) = \max(0, o_{i})$, where $f(o)$ is the ReLU function. We provide class predictions $\hat{y}$ through argmax function, i.e. argmax $f(x)$.

##### Abstract (translated by Google)
我们引入整流线性单元（ReLU）作为深度神经网络（DNN）中的分类函数。传统上，ReLU被用作DNN中的激活功能，其中Softmax功能作为其分类功能。但是，有几项关于使用除Softmax以外的分类功能的研究，本研究是对这些研究的补充。我们通过在神经网络中激活倒数第二层$ h_ {n-1} $来实现这一点，然后将它乘以权重参数$ \ theta $得到原始分数$ o_ {i} $。之后，我们将原始分数$ o_ {i} $限定为$ 0 $，即$ f（o）= \ max（0，o_ {i}）$，其中$ f（o）$是ReLU函数。我们通过argmax函数提供类别预测$ \ hat {y} $，即argmax $ f（x）$。

##### URL
[https://arxiv.org/abs/1803.08375](https://arxiv.org/abs/1803.08375)

##### PDF
[https://arxiv.org/pdf/1803.08375](https://arxiv.org/pdf/1803.08375)

