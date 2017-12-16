---
layout: post
title: "Optimization on Product Submanifolds of Convolution Kernels"
date: 2017-11-27 09:08:19
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Mete Ozay, Takayuki Okatani
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in optimization methods used for training convolutional neural networks (CNNs) with kernels, which are normalized according to particular constraints, have shown remarkable success. This work introduces an approach for training CNNs using ensembles of joint spaces of kernels constructed using different constraints. For this purpose, we address a problem of optimization on ensembles of products of submanifolds (PEMs) of convolution kernels. To this end, we first propose three strategies to construct ensembles of PEMs in CNNs. Next, we expound their geometric properties (metric and curvature properties) in CNNs. We make use of our theoretical results by developing a geometry-aware SGD algorithm (G-SGD) for optimization on ensembles of PEMs to train CNNs. Moreover, we analyze convergence properties of G-SGD considering geometric properties of PEMs. In the experimental analyses, we employ G-SGD to train CNNs on Cifar-10, Cifar-100 and Imagenet datasets. The results show that geometric adaptive step size computation methods of G-SGD can improve training loss and convergence properties of CNNs. Moreover, we observe that classification performance of baseline CNNs can be boosted using G-SGD on ensembles of PEMs identified by multiple constraints.

##### Abstract (translated by Google)
用于训练具有核心的卷积神经网络（CNN）的优化方法的最新进展已经显示出显着的成功。这项工作介绍了一种使用不同约束条件构建的核心联合空间集合训练CNN的方法。为此，我们解决了卷积核子流形（PEMs）乘积的优化问题。为此，我们首先提出三种策略在CNNs中构建PEMs集合。接下来，我们在CNN中阐述它们的几何特性（公制和曲率特性）。我们利用我们的理论成果开发了几何感知的SGD算法（G-SGD）来优化PEM系统来训练CNN。此外，我们分析考虑PEM的几何性质的G-SGD的收敛性质。在实验分析中，我们使用G-SGD在Cifar-10，Cifar-100和Imagenet数据集上训练CNN。结果表明，G-SGD的几何自适应步长计算方法可以提高CNN的训练损失和收敛性能。此外，我们观察到基线CNNs的分类性能可以通过使用G-SGD在由多个约束条件识别的PEM集合上得到提高。

##### URL
[https://arxiv.org/abs/1701.06123](https://arxiv.org/abs/1701.06123)

##### PDF
[https://arxiv.org/pdf/1701.06123](https://arxiv.org/pdf/1701.06123)

