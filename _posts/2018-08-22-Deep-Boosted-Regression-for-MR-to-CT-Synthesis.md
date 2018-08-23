---
layout: post
title: "Deep Boosted Regression for MR to CT Synthesis"
date: 2018-08-22 16:40:22
categories: arXiv_AI
tags: arXiv_AI Segmentation CNN Quantitative
author: Kerstin Kl&#xe4;ser, Pawel Markiewicz, Marta Ranzini, Wenqi Li, Marc Modat, Brian F Hutton, David Atkinson, Kris Thielemans, M Jorge Cardoso, Sebastien Ourselin
mathjax: true
---

* content
{:toc}

##### Abstract
Attenuation correction is an essential requirement of positron emission tomography (PET) image reconstruction to allow for accurate quantification. However, attenuation correction is particularly challenging for PET-MRI as neither PET nor magnetic resonance imaging (MRI) can directly image tissue attenuation properties. MRI-based computed tomography (CT) synthesis has been proposed as an alternative to physics based and segmentation-based approaches that assign a population-based tissue density value in order to generate an attenuation map. We propose a novel deep fully convolutional neural network that generates synthetic CTs in a recursive manner by gradually reducing the residuals of the previous network, increasing the overall accuracy and generalisability, while keeping the number of trainable parameters within reasonable limits. The model is trained on a database of 20 pre-acquired MRI/CT pairs and a four-fold random bootstrapped validation with a 80:20 split is performed. Quantitative results show that the proposed framework outperforms a state-of-the-art atlas-based approach decreasing the Mean Absolute Error (MAE) from 131HU to 68HU for the synthetic CTs and reducing the PET reconstruction error from 14.3% to 7.2%.

##### Abstract (translated by Google)
衰减校正是正电子发射断层扫描（PET）图像重建的基本要求，以允许准确的量化。然而，衰减校正对于PET-MRI尤其具有挑战性，因为PET和磁共振成像（MRI）都不能直接成像组织衰减特性。已经提出基于MRI的计算机断层扫描（CT）合成作为基于物理和基于分割的方法的替代方案，其分配基于群体的组织密度值以便生成衰减图。我们提出了一种新颖的深度完全卷积神经网络，通过逐步减少先前网络的残差，提高整体准确性和通用性，同时将可训练参数的数量保持在合理的限度内，以递归方式生成合成CT。该模型在20个预先获得的MRI / CT对的数据库上训练，并且执行具有80:20分割的四倍随机自举验证。定量的结果表明，所提出的框架优于一个国家的最先进的基于图谱的方法降低了平均绝对误差（MAE）从131HU到68HU用于合成CT和降低PET重建误差从14.3％到7.2％。

##### URL
[http://arxiv.org/abs/1808.07431](http://arxiv.org/abs/1808.07431)

##### PDF
[http://arxiv.org/pdf/1808.07431](http://arxiv.org/pdf/1808.07431)

