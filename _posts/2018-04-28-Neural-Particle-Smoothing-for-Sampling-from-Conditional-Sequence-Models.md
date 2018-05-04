---
layout: post
title: "Neural Particle Smoothing for Sampling from Conditional Sequence Models"
date: 2018-04-28 06:10:45
categories: arXiv_CL
tags: arXiv_CL RNN
author: Chu-Cheng Lin, Jason Eisner
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce neural particle smoothing, a sequential Monte Carlo method for sampling annotations of an input string from a given probability model. In contrast to conventional particle filtering algorithms, we train a proposal distribution that looks ahead to the end of the input string by means of a right-to-left LSTM. We demonstrate that this innovation can improve the quality of the sample. To motivate our formal choices, we explain how our neural model and neural sampler can be viewed as low-dimensional but nonlinear approximations to working with HMMs over very large state spaces.

##### Abstract (translated by Google)
我们引入了神经粒子平滑，一种顺序蒙特卡罗方法，用于从给定的概率模型中抽取输入字符串的注释。与传统的粒子滤波算法不同，我们通过从右到左的LSTM来训练一个提案分布，该分布预测输入字符串的末尾。我们证明这一创新可以提高样品的质量。为了激励我们的正式选择，我们解释了我们的神经模型和神经采样器如何被看作是在非常大的状态空间中与HMM一起工作的低维但非线性逼近。

##### URL
[https://arxiv.org/abs/1804.10747](https://arxiv.org/abs/1804.10747)

##### PDF
[https://arxiv.org/pdf/1804.10747](https://arxiv.org/pdf/1804.10747)

