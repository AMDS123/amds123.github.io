---
layout: post
title: "Decouple Learning for Parameterized Image Operators"
date: 2018-07-21 17:58:54
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Qingnan Fan, Dongdong Chen, Lu Yuan, Gang Hua, Nenghai Yu, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Many different deep networks have been used to approximate, accelerate or improve traditional image operators, such as image smoothing, super-resolution and denoising. Among these traditional operators, many contain parameters which need to be tweaked to obtain the satisfactory results, which we refer to as "parameterized image operators". However, most existing deep networks trained for these operators are only designed for one specific parameter configuration, which does not meet the needs of real scenarios that usually require flexible parameters settings. To overcome this limitation, we propose a new decouple learning algorithm to learn from the operator parameters to dynamically adjust the weights of a deep network for image operators, denoted as the base network. The learned algorithm is formed as another network, namely the weight learning network, which can be end-to-end jointly trained with the base network. Experiments demonstrate that the proposed framework can be successfully applied to many traditional parameterized image operators. We provide more analysis to better understand the proposed framework, which may inspire more promising research in this direction. Our codes and models have been released in 
 https://github.com/fqnchina/DecoupleLearning.

##### Abstract (translated by Google)
已经使用许多不同的深度网络来近似，加速或改进传统的图像算子，例如图像平滑，超分辨率和去噪。在这些传统的运算符中，许多包含需要调整的参数以获得令人满意的结果，我们将其称为“参数化图像运算符”。然而，为这些运营商训练的大多数现有深度网络仅针对一种特定参数配置而设计，其不满足通常需要灵活参数设置的真实场景的需要。为了克服这个限制，我们提出了一种新的解耦学习算法，以便从运营商参数中学习，为图像运营商动态调整深度网络的权重，表示为基础网络。学习算法形成为另一个网络，即权重学习网络，其可以与基础网络进行端到端的联合训练。实验证明，所提出的框架可以成功地应用于许多传统的参数化图像算子。我们提供更多分析以更好地理解所提出的框架，这可能会激发更有希望的研究方向。我们的代码和模型已发布
 https://github.com/fqnchina/DecoupleLearning。

##### URL
[http://arxiv.org/abs/1807.08186](http://arxiv.org/abs/1807.08186)

##### PDF
[http://arxiv.org/pdf/1807.08186](http://arxiv.org/pdf/1807.08186)

