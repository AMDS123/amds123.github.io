---
layout: post
title: "Stochastic Downsampling for Cost-Adjustable Inference and Improved Regularization in Convolutional Networks"
date: 2018-01-29 01:16:03
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Image_Classification Inference Classification Prediction
author: Jason Kuen, Xiangfei Kong, Zhe Lin, Gang Wang, Jianxiong Yin, Simon See, Yap-Peng Tan
mathjax: true
---

* content
{:toc}

##### Abstract
It is desirable to train convolutional networks (CNNs) to run more efficiently during inference. In many cases however, the computational budget that the system has for inference cannot be known beforehand during training, or the inference budget is dependent on the changing real-time resource availability. Thus, it is inadequate to train just inference-efficient CNNs, whose inference costs are not adjustable and cannot adapt to varied inference budgets. We propose a novel approach for cost-adjustable inference in CNNs - Stochastic Downsampling Point (SDPoint). During training, SDPoint applies feature map downsampling to a random point in the layer hierarchy, with a random downsampling ratio. The different stochastic downsampling configurations known as SDPoint instances (of the same model) have computational costs different from each other, while being trained to minimize the same prediction loss. Sharing network parameters across different instances provides significant regularization boost. During inference, one may handpick a SDPoint instance that best fits the inference budget. The effectiveness of SDPoint, as both a cost-adjustable inference approach and a regularizer, is validated through extensive experiments on image classification.

##### Abstract (translated by Google)
训练卷积网络（CNN）在推理期间更有效地运行是可取的。然而，在很多情况下，系统推理的计算预算在训练期间不能预先知道，或者推理预算取决于变化的实时资源可用性。因此，仅仅推理有效的CNN是不够的，其推理成本是不可调整的，不能适应不同的推理预算。我们提出了一种新颖的CNNs随机下采样点（SDPoint）可调成本推断方法。在训练期间，SDPoint将特征映射下采样应用于层级中的随机点，并具有随机下采样比率。称为SDPoint实例（相同模型）的不同随机缩减采样配置具有彼此不同的计算成本，同时被训练以最小化相同的预测损失。在不同实例之间共享网络参数提供了显着的正则化提升。在推断过程中，可以手工挑选最适合推理预算的SDPoint实例。 SDPoint作为成本可调的推理方法和正规化器的有效性通过对图像分类的广泛实验来验证。

##### URL
[http://arxiv.org/abs/1801.09335](http://arxiv.org/abs/1801.09335)

##### PDF
[http://arxiv.org/pdf/1801.09335](http://arxiv.org/pdf/1801.09335)

