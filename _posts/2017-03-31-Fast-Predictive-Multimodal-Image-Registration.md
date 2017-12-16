---
layout: post
title: "Fast Predictive Multimodal Image Registration"
date: 2017-03-31 14:05:57
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction Relation
author: Xiao Yang, Roland Kwitt, Martin Styner, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a deep encoder-decoder architecture for image deformation prediction from multimodal images. Specifically, we design an image-patch-based deep network that jointly (i) learns an image similarity measure and (ii) the relationship between image patches and deformation parameters. While our method can be applied to general image registration formulations, we focus on the Large Deformation Diffeomorphic Metric Mapping (LDDMM) registration model. By predicting the initial momentum of the shooting formulation of LDDMM, we preserve its mathematical properties and drastically reduce the computation time, compared to optimization-based approaches. Furthermore, we create a Bayesian probabilistic version of the network that allows evaluation of registration uncertainty via sampling of the network at test time. We evaluate our method on a 3D brain MRI dataset using both T1- and T2-weighted images. Our experiments show that our method generates accurate predictions and that learning the similarity measure leads to more consistent registrations than relying on generic multimodal image similarity measures, such as mutual information. Our approach is an order of magnitude faster than optimization-based LDDMM.

##### Abstract (translated by Google)
我们介绍了一种深度编码器 - 解码器架构，用于从多模态图像预测图像变形。具体而言，我们设计了一个基于图像斑块的深度网络，这个网络共同（i）学习一个图像相似性度量和（ii）图像块和变形参数之间的关系。虽然我们的方法可以应用于一般的图像配准公式，但我们关注的是大变形微分形式度量映射（LDDMM）配准模型。通过预测LDDMM射击公式的初始动量，与基于优化的方法相比，我们保留了它的数学特性并大大减少了计算时间。此外，我们创建了网络的贝叶斯概率版本，允许通过在测试时间采样网络来评估注册不确定性。我们使用T1和T2加权图像在3D脑部MRI数据集上评估我们的方法。我们的实验表明，我们的方法产生准确的预测，并且学习相似性度量导致比依赖通用多模式图像相似性度量如互信息更一致的注册。我们的方法比基于优化的LDDMM快一个数量级。

##### URL
[https://arxiv.org/abs/1703.10902](https://arxiv.org/abs/1703.10902)

##### PDF
[https://arxiv.org/pdf/1703.10902](https://arxiv.org/pdf/1703.10902)

