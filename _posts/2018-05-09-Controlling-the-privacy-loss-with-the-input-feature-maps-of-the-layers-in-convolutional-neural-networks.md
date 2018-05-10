---
layout: post
title: "Controlling the privacy loss with the input feature maps of the layers in convolutional neural networks"
date: 2018-05-09 10:12:31
categories: arXiv_CV
tags: arXiv_CV CNN
author: Woohyung Chun, Sung-Min Hong, Junho Huh, Inyup Kang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the method to sanitize the privacy of the IFM(Input Feature Map)s that are fed into the layers of CNN(Convolutional Neural Network)s. The method introduces the degree of the sanitization that makes the application using a CNN be able to control the privacy loss represented as the ratio of the probabilistic accuracies for original IFM(Input Feature Map) and sanitized IFM. For the sanitization of an IFM, the sample-and-hold based approximation scheme is devised to satisfy an application-specific degree of the sanitization. The scheme approximates an IFM by replacing all the samples in a window with the non-zero sample closest to the mean of the sampling window. It also removes the dependency on CNN configuration by unfolding multi-dimensional IFM tensors into one-dimensional streams to be approximated.

##### Abstract (translated by Google)
我们提出了消除馈送到CNN（卷积神经网络）层的IFM（输入特征映射）的隐私的方法。该方法引入了使得使用CNN的应用程序能够控制隐私损失的卫生程度，该隐私损失表示为用于原始IFM（输入特征图）和经过消毒的IFM的概率精度的比率。为了对IFM进行消毒，基于采样和保持的近似方案被设计为满足消毒过程的特定应用程度。该方案通过将窗口中的所有样本替换为最接近采样窗口平均值的非零样本来近似IFM。它还通过将多维IFM张量展开为近似的一维流来消除对CNN配置的依赖。

##### URL
[http://arxiv.org/abs/1805.03444](http://arxiv.org/abs/1805.03444)

##### PDF
[http://arxiv.org/pdf/1805.03444](http://arxiv.org/pdf/1805.03444)

