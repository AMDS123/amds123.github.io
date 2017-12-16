---
layout: post
title: "On Image Classification: Correlation v.s. Causality"
date: 2017-08-22 14:49:07
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Relation
author: Zheyan Shen, Peng Cui, Kun Kuang, Bo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Image classification is one of the fundamental problems in computer vision. Owing to the availability of large image datasets like ImageNet and YFCC100M, a plethora of research has been conducted to do high precision image classification and many remarkable achievements have been made. The success of most existing methods hinges on a basic hypothesis that the testing image set has the same distribution as the training image set. However, in many real applications, we cannot guarantee the validity of the i.i.d. hypothesis since the testing image set is unseen. It is thus desirable to learn an image classifier, which can perform well even in non-i.i.d. situations. In this paper, we propose a novel Causally Regularized Logistic Regression (CRLR) algorithm to address the non-i.i.d. problem without knowing testing data information by searching for causal features. The causal features refer to characteristics truly determining whether a special object belongs to a category or not. Algorithmically, we propose a causal regularizer for causal feature identification by jointly optimizing it with a logistic loss term. Assisted with the causal regularizer, we can estimate the causal contribution (causal effect) of each focal image feature (viewed as a treatment variable) by sample reweighting which ensures the distributions of all remaining image features between images with different focal feature levels are close. The resultant classifier will be based on the estimated causal contributions of the features, rather than traditional correlation-based contributions. To validate the e effectiveness of our CRLR algorithm, we manually construct a new image dataset from YFCC100M, simulating various non-i.i.d. situations in the real world, and conduct extensive experiments for image classification. Experimental results clearly demonstrate that our CRLR algorithm outperforms the state-of-the-art methods.

##### Abstract (translated by Google)
图像分类是计算机视觉中的一个基本问题。由于ImageNet，YFCC100M等大型图像数据集的可用性，进行了大量的高精度图像分类研究，取得了显着的成果。大多数现有方法的成功取决于测试图像集与训练图像集具有相同分布的基本假设。但是，在很多实际应用中，我们不能保证i.i.d的有效性。因为测试图像集是不可见的假设。因此，需要学习一个图像分类器，即使在非i.i.d中也可以很好地执行。的情况。在本文中，我们提出了一种新的因果规则化Logistic回归（CRLR）算法来解决非i.i.d。问题而不知道通过搜索因果特征来测试数据信息。因果特征是指真正确定特定对象是否属于某个类别的特征。在算法上，我们提出了因果特征识别的因果调节因子，通过与逻辑损失项联合优化。通过辅助因果调节器，我们可以通过样本重新调整来估计每个焦点图像特征（作为处理变量）的因果贡献（因果效应），确保具有不同焦点特征水平的图像之间的所有剩余图像特征的分布相近。由此产生的分类器将基于特征的估计因果贡献，而不是传统的基于相关性的贡献。为了验证CRLR算法的有效性，我们从YFCC100M手动构建一个新的图像数据集，模拟各种非i.i.d。在现实世界中的情况，并进行广泛的图像分类实验。实验结果清楚地表明，我们的CRLR算法胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1708.06656](https://arxiv.org/abs/1708.06656)

##### PDF
[https://arxiv.org/pdf/1708.06656](https://arxiv.org/pdf/1708.06656)

