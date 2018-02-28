---
layout: post
title: "Coarse to fine non-rigid registration: a chain of scale-specific neural networks for multimodal image alignment with application to remote sensing"
date: 2018-02-27 10:47:06
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Gradient_Descent
author: Armand Zampieri (TITANE), Guillaume Charpiat (TAU), Yuliya Tarabalka (TITANE)
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle here the problem of multimodal image non-rigid registration, which is of prime importance in remote sensing and medical imaging. The difficulties encountered by classical registration approaches include feature design and slow optimization by gradient descent. By analyzing these methods, we note the significance of the notion of scale. We design easy-to-train, fully-convolutional neural networks able to learn scale-specific features. Once chained appropriately, they perform global registration in linear time, getting rid of gradient descent schemes by predicting directly the deformation.We show their performance in terms of quality and speed through various tasks of remote sensing multimodal image alignment. In particular, we are able to register correctly cadastral maps of buildings as well as road polylines onto RGB images, and outperform current keypoint matching methods.

##### Abstract (translated by Google)
我们在这里解决多模态图像非刚性配准问题，这在遥感和医学成像中是非常重要的。经典注册方法遇到的困难包括特征设计和梯度下降的缓慢优化。通过分析这些方法，我们注意到规模概念的重要性。我们设计了易于训练的全卷积神经网络，能够学习特定尺度的特征。一旦适当链接，它们将在线性时间内执行全局配准，通过直接预测变形消除梯度下降方案。我们通过遥感多模图像对齐的各种任务，在质量和速度方面显示其性能。特别是，我们能够正确注册建筑物的地籍图以及道路多段线到RGB图像上，并且胜过当前的关键点匹配方法。

##### URL
[https://arxiv.org/abs/1802.09816](https://arxiv.org/abs/1802.09816)

##### PDF
[https://arxiv.org/pdf/1802.09816](https://arxiv.org/pdf/1802.09816)

