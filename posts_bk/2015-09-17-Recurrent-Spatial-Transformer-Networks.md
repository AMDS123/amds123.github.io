---
layout: post
title: "Recurrent Spatial Transformer Networks"
date: 2015-09-17 16:50:29
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Søren Kaae Sønderby, Casper Kaae Sønderby, Lars Maaløe, Ole Winther
mathjax: true
---

* content
{:toc}

##### Abstract
We integrate the recently proposed spatial transformer network (SPN) [Jaderberg et. al 2015] into a recurrent neural network (RNN) to form an RNN-SPN model. We use the RNN-SPN to classify digits in cluttered MNIST sequences. The proposed model achieves a single digit error of 1.5% compared to 2.9% for a convolutional networks and 2.0% for convolutional networks with SPN layers. The SPN outputs a zoomed, rotated and skewed version of the input image. We investigate different down-sampling factors (ratio of pixel in input and output) for the SPN and show that the RNN-SPN model is able to down-sample the input images without deteriorating performance. The down-sampling in RNN-SPN can be thought of as adaptive down-sampling that minimizes the information loss in the regions of interest. We attribute the superior performance of the RNN-SPN to the fact that it can attend to a sequence of regions of interest.

##### Abstract (translated by Google)
我们整合了最近提出的空间变压器网络（SPN）[Jaderberg et。 （2015）]转化为递归神经网络（RNN）以形成RNN-SPN模型。我们使用RNN-SPN来对杂乱的MNIST序列中的数字进行分类。所提出的模型实现1.5％的单位数字误差，卷积网络为2.9％，SPN层卷积网络为2.0％。 SPN输出缩放，旋转和倾斜版本的输入图像。我们研究了SPN的不同下采样因子（输入和输出像素的比例），并证明RNN-SPN模型能够对输入图像进行下采样而不降低性能。 RNN-SPN中的下采样可以被认为是自适应下采样，其使感兴趣区域中的信息损失最小化。我们将RNN-SPN的优越性能归因于它能够关注一系列感兴趣的区域。

##### URL
[https://arxiv.org/abs/1509.05329](https://arxiv.org/abs/1509.05329)

##### PDF
[https://arxiv.org/pdf/1509.05329](https://arxiv.org/pdf/1509.05329)

