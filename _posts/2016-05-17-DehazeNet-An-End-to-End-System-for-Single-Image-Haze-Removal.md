---
layout: post
title: "DehazeNet: An End-to-End System for Single Image Haze Removal"
date: 2016-05-17 08:03:18
categories: arXiv_CV
tags: arXiv_CV CNN
author: Bolun Cai, Xiangmin Xu, Kui Jia, Chunmei Qing, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Single image haze removal is a challenging ill-posed problem. Existing methods use various constraints/priors to get plausible dehazing solutions. The key to achieve haze removal is to estimate a medium transmission map for an input hazy image. In this paper, we propose a trainable end-to-end system called DehazeNet, for medium transmission estimation. DehazeNet takes a hazy image as input, and outputs its medium transmission map that is subsequently used to recover a haze-free image via atmospheric scattering model. DehazeNet adopts Convolutional Neural Networks (CNN) based deep architecture, whose layers are specially designed to embody the established assumptions/priors in image dehazing. Specifically, layers of Maxout units are used for feature extraction, which can generate almost all haze-relevant features. We also propose a novel nonlinear activation function in DehazeNet, called Bilateral Rectified Linear Unit (BReLU), which is able to improve the quality of recovered haze-free image. We establish connections between components of the proposed DehazeNet and those used in existing methods. Experiments on benchmark images show that DehazeNet achieves superior performance over existing methods, yet keeps efficient and easy to use.

##### Abstract (translated by Google)
单个图像阴霾清除是一个具有挑战性的不适合的问题。现有方法使用各种约束/先验来获得合理的去雾解决方案。实现霾去除的关键是估算输入模糊图像的中等透射图。在本文中，我们提出了一个名为DehazeNet的可训练端到端系统，用于中等传输估计。 DehazeNet将朦胧的图像作为输入，输出其中等透射图，随后用于通过大气散射模型恢复无雾图像。 DehazeNet采用基于卷积神经网络（CNN）的深层架构，其层次经过专门设计，以体现图像去雾方面的既定假设/先验。具体来说，Maxout单位的层被用于特征提取，其可以产生几乎所有与雾度有关的特征。我们还提出了DehazeNet中的一种新的非线性激活函数，称为双边校正线性单元（BReLU），它能够提高回收的无雾图像的质量。我们在建议的DehazeNet的组件和现有方法中使用的组件之间建立连接。基准图像的实验表明，DehazeNet实现了超越现有方法的卓越性能，而且保持高效和易于使用。

##### URL
[https://arxiv.org/abs/1601.07661](https://arxiv.org/abs/1601.07661)

##### PDF
[https://arxiv.org/pdf/1601.07661](https://arxiv.org/pdf/1601.07661)

