---
layout: post
title: "Regularizing Deep Neural Networks by Noise: Its Interpretation and Optimization"
date: 2017-11-09 13:50:43
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Gradient_Descent
author: Hyeonwoo Noh, Tackgeun You, Jonghwan Mun, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
Overfitting is one of the most critical challenges in deep neural networks, and there are various types of regularization methods to improve generalization performance. Injecting noises to hidden units during training, e.g., dropout, is known as a successful regularizer, but it is still not clear enough why such training techniques work well in practice and how we can maximize their benefit in the presence of two conflicting objectives---optimizing to true data distribution and preventing overfitting by regularization. This paper addresses the above issues by 1) interpreting that the conventional training methods with regularization by noise injection optimize the lower bound of the true objective and 2) proposing a technique to achieve a tighter lower bound using multiple noise samples per training example in a stochastic gradient descent iteration. We demonstrate the effectiveness of our idea in several computer vision applications.

##### Abstract (translated by Google)
过度拟合是深度神经网络中最为关键的挑战之一，并且存在各种类型的正则化方法来提高泛化性能。在训练期间向隐蔽单位注射噪音，例如辍学，被称为成功的正规化者，但是仍然不够清楚，为什么这种训练技术在实践中运作良好，以及如何在存在两个相互冲突的目标的情况下最大化他们的利益 -  - 优化真正的数据分布并防止正规化过度拟合。本文通过以下方面解决了上述问题：1）通过噪声注入正则化的传统训练方法优化了真实目标的下限，并且2）提出了在每个训练示例中使用多个噪声样本实现更紧密下限的技术梯度下降迭代。我们在几个计算机视觉应用中展示了我们的想法的有效性。

##### URL
[https://arxiv.org/abs/1710.05179](https://arxiv.org/abs/1710.05179)

##### PDF
[https://arxiv.org/pdf/1710.05179](https://arxiv.org/pdf/1710.05179)

