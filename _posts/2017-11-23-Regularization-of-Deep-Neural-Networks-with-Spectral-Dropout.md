---
layout: post
title: "Regularization of Deep Neural Networks with Spectral Dropout"
date: 2017-11-23 06:47:37
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Relation
author: Salman Khan, Munawar Hayat, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
The big breakthrough on the ImageNet challenge in 2012 was partially due to the `dropout' technique used to avoid overfitting. Here, we introduce a new approach called `Spectral Dropout' to improve the generalization ability of deep neural networks. We cast the proposed approach in the form of regular Convolutional Neural Network (CNN) weight layers using a decorrelation transform with fixed basis functions. Our spectral dropout method prevents overfitting by eliminating weak and `noisy' Fourier domain coefficients of the neural network activations, leading to remarkably better results than the current regularization methods. Furthermore, the proposed is very efficient due to the fixed basis functions used for spectral transformation. In particular, compared to Dropout and Drop-Connect, our method significantly speeds up the network convergence rate during the training process (roughly x2), with considerably higher neuron pruning rates (an increase of ~ 30%). We demonstrate that the spectral dropout can also be used in conjunction with other regularization approaches resulting in additional performance gains.

##### Abstract (translated by Google)
2012年ImageNet挑战的重大突破部分归因于用于避免过度配合的“辍学”技术。在这里，我们引入了一种叫做“光谱丢弃”的新方法来提高深度神经网络的泛化能力。我们使用具有固定基函数的解相关变换，以常规卷积神经网络（CNN）权重层的形式来提出所提出的方法。我们的光谱丢失方法通过消除神经网络激活的弱和“噪声”傅里叶域系数来防止过拟合，导致比当前的正则化方法显着更好的结果。此外，由于用于频谱变换的固定基函数，所提出的非常高效。特别是与Dropout和Drop-Connect相比，我们的方法显着加快了训练过程中的网络收敛速度（大概x2），神经元修剪速率更高（增加了30％）。我们证明光谱衰减也可以与其他正则化方法结合使用，从而获得额外的性能收益。

##### URL
[https://arxiv.org/abs/1711.08591](https://arxiv.org/abs/1711.08591)

##### PDF
[https://arxiv.org/pdf/1711.08591](https://arxiv.org/pdf/1711.08591)

