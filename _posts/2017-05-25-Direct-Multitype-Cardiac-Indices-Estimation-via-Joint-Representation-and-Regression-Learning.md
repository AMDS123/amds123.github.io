---
layout: post
title: "Direct Multitype Cardiac Indices Estimation via Joint Representation and Regression Learning"
date: 2017-05-25 18:01:41
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation CNN
author: Wufeng Xue, Ali Islam, Mousumi Bhaduri, Shuo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac indices estimation is of great importance during identification and diagnosis of cardiac disease in clinical routine. However, estimation of multitype cardiac indices with consistently reliable and high accuracy is still a great challenge due to the high variability of cardiac structures and complexity of temporal dynamics in cardiac MR sequences. While efforts have been devoted into cardiac volumes estimation through feature engineering followed by a independent regression model, these methods suffer from the vulnerable feature representation and incompatible regression model. In this paper, we propose a semi-automated method for multitype cardiac indices estimation. After manual labelling of two landmarks for ROI cropping, an integrated deep neural network Indices-Net is designed to jointly learn the representation and regression models. It comprises two tightly-coupled networks: a deep convolution autoencoder (DCAE) for cardiac image representation, and a multiple output convolution neural network (CNN) for indices regression. Joint learning of the two networks effectively enhances the expressiveness of image representation with respect to cardiac indices, and the compatibility between image representation and indices regression, thus leading to accurate and reliable estimations for all the cardiac indices. When applied with five-fold cross validation on MR images of 145 subjects, Indices-Net achieves consistently low estimation error for LV wall thicknesses (1.44$\pm$0.71mm) and areas of cavity and myocardium (204$\pm$133mm$^2$). It outperforms, with significant error reductions, segmentation method (55.1% and 17.4%) and two-phase direct volume-only methods (12.7% and 14.6%) for wall thicknesses and areas, respectively. These advantages endow the proposed method a great potential in clinical cardiac function assessment.

##### Abstract (translated by Google)
心脏指数估计在临床常规心脏疾病的鉴别和诊断中具有重要意义。然而，由于心脏结构的高度可变性和心脏MR序列中时间动态的复杂性，对一致可靠和高准确度的多指标心脏指数的估计仍然是一个巨大的挑战。尽管已经通过特征工程和独立回归模型对心脏体积进行了估计，但这些方法都存在脆弱的特征表征和不相容的回归模型。在本文中，我们提出了一种用于多指标心脏指数估计的半自动化方法。在为ROI裁剪手工标记两个地标之后，集成的深度神经网络Indices-Net被设计为联合学习表示和回归模型。它包括两个紧密耦合的网络：用于心脏图像表示的深度卷积自编码器（DCAE）和用于指数回归的多输出卷积神经网络（CNN）。两网络的联合学习有效地提高了图像表示与心脏指标的表现力，以及图像表示与指标回归之间的兼容性，从而导致对所有心脏指标的准确可靠的估计。当在145名受试者的MR图像上应用5倍交叉验证时，Indices-Net对于LV壁厚度（1.44 $ / pm $ 0.71mm）以及腔和心肌的面积（204 $ \ pm $ 133mm $ ^ 2 $）。对于墙壁厚度和面积而言，其性能优于误差显着性降低，分割方法（55.1％和17.4％）和两相直接体积法（12.7％和14.6％）。这些优点赋予所提出的方法在临床心脏功能评估上的巨大潜力。

##### URL
[https://arxiv.org/abs/1705.09307](https://arxiv.org/abs/1705.09307)

##### PDF
[https://arxiv.org/pdf/1705.09307](https://arxiv.org/pdf/1705.09307)

