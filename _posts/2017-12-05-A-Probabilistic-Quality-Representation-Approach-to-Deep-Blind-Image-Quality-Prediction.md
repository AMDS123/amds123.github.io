---
layout: post
title: 'A Probabilistic Quality Representation Approach to Deep Blind Image Quality Prediction'
date: 2017-12-06 09:54:14
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Hui Zeng, Lei Zhang, Alan C. Bovik
---

* content
{:toc}

##### Abstract
Blind image quality assessment (BIQA) remains a very challenging problem due to the unavailability of a reference image. Deep learning based BIQA methods have been attracting increasing attention in recent years, yet it remains a difficult task to train a robust deep BIQA model because of the very limited number of training samples with human subjective scores. Most existing methods learn a regression network to minimize the prediction error of a scalar image quality score. However, such a scheme ignores the fact that an image will receive divergent subjective scores from different subjects, which cannot be adequately represented by a single scalar number. This is particularly true on complex, real-world distorted images. Moreover, images may broadly differ in their distributions of assigned subjective scores. Recognizing this, we propose a new representation of perceptual image quality, called probabilistic quality representation (PQR), to describe the image subjective score distribution, whereby a more robust loss function can be employed to train a deep BIQA model. The proposed PQR method is shown to not only speed up the convergence of deep model training, but to also greatly improve the achievable level of quality prediction accuracy relative to scalar quality score regression methods. The source code is available at https://github.com/HuiZeng/BIQA_Toolbox.

##### Abstract (translated by Google)
由于参考图像的不可用性，盲图像质量评估（BIQA）仍然是一个非常具有挑战性的问题。基于深度学习的BIQA方法近年来受到越来越多的关注，但由于人为主观评分训练样本的数量非常有限，因此训练一个稳健的深度BIQA模型仍然是一项艰巨的任务。大多数现有方法学习回归网络以最小化标量图像质量分数的预测误差。然而，这样的方案忽略了一个事实，一个图像将收到来自不同主体的不同的主观分数，这不能用一个单一的标量数来充分表示。对于复杂的现实世界的失真图像尤其如此。此外，图像在分配的主观分数的分布上可能大不相同。认识到这一点，我们提出了一种感知图像质量的新表示，称为概率质量表示（PQR），用来描述图像的主观评分分布，从而可以采用更稳健的损失函数来训练深度的BIQA模型。所提出的PQR方法不仅能加快深层模型训练的收敛速度，而且相对于标量质量分数回归方法，也大大提高了质量预测准确度的可达到的水平。源代码可在https://github.com/HuiZeng/BIQA_Toolbox上找到。

##### URL
[http://arxiv.org/abs/1708.08190](http://arxiv.org/abs/1708.08190)

