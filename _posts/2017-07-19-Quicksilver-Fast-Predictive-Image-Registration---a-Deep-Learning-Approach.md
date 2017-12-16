---
layout: post
title: "Quicksilver: Fast Predictive Image Registration - a Deep Learning Approach"
date: 2017-07-19 18:40:48
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Deep_Learning Prediction
author: Xiao Yang, Roland Kwitt, Martin Styner, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces Quicksilver, a fast deformable image registration method. Quicksilver registration for image-pairs works by patch-wise prediction of a deformation model based directly on image appearance. A deep encoder-decoder network is used as the prediction model. While the prediction strategy is general, we focus on predictions for the Large Deformation Diffeomorphic Metric Mapping (LDDMM) model. Specifically, we predict the momentum-parameterization of LDDMM, which facilitates a patch-wise prediction strategy while maintaining the theoretical properties of LDDMM, such as guaranteed diffeomorphic mappings for sufficiently strong regularization. We also provide a probabilistic version of our prediction network which can be sampled during the testing time to calculate uncertainties in the predicted deformations. Finally, we introduce a new correction network which greatly increases the prediction accuracy of an already existing prediction network. We show experimental results for uni-modal atlas-to-image as well as uni- / multi- modal image-to-image registrations. These experiments demonstrate that our method accurately predicts registrations obtained by numerical optimization, is very fast, achieves state-of-the-art registration results on four standard validation datasets, and can jointly learn an image similarity measure. Quicksilver is freely available as an open-source software.

##### Abstract (translated by Google)
本文介绍了Quicksilver，一种快速变形的图像配准方法。图像对的Quicksilver配准通过直接基于图像外观的变形模型的拼片式预测来工作。使用深度编码器 - 解码器网络作为预测模型。虽然预测策略是一般性的，但我们关注的是大变形微分形式度量映射（LDDMM）模型的预测。具体而言，我们预测了LDDMM的动量参数化，这有助于在保持LDDMM的理论性质（例如具有足够强的正则化的保证的微分同胚映射）的同时实现面片预测策略。我们还提供了一个概率版本的预测网络，可以在测试时间内采样，以计算预测变形的不确定性。最后引入一个新的校正网络，大大提高了现有预测网络的预测精度。我们展示了单模式图像到图像以及单/多模式图像到图像配准的实验结果。这些实验表明，我们的方法准确地预测通过数值优化获得的配准，速度非常快，在四个标准验证数据集上实现了最新的配准结果，并且可以共同学习图像相似性度量。 Quicksilver作为一个开源软件可以免费获得。

##### URL
[https://arxiv.org/abs/1703.10908](https://arxiv.org/abs/1703.10908)

##### PDF
[https://arxiv.org/pdf/1703.10908](https://arxiv.org/pdf/1703.10908)

