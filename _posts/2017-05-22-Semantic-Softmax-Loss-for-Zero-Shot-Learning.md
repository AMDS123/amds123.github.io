---
layout: post
title: "Semantic Softmax Loss for Zero-Shot Learning"
date: 2017-05-22 12:26:04
categories: arXiv_CV
tags: arXiv_CV Embedding Classification
author: Zhong Ji, Yunxin Sun, Yulong Yu, Jichang Guo, Yanwei Pang
mathjax: true
---

* content
{:toc}

##### Abstract
A typical pipeline for Zero-Shot Learning (ZSL) is to integrate the visual features and the class semantic descriptors into a multimodal framework with a linear or bilinear model. However, the visual features and the class semantic descriptors locate in different structural spaces, a linear or bilinear model can not capture the semantic interactions between different modalities well. In this letter, we propose a nonlinear approach to impose ZSL as a multi-class classification problem via a Semantic Softmax Loss by embedding the class semantic descriptors into the softmax layer of multi-class classification network. To narrow the structural differences between the visual features and semantic descriptors, we further use an L2 normalization constraint to the differences between the visual features and visual prototypes reconstructed with the semantic descriptors. The results on three benchmark datasets, i.e., AwA, CUB and SUN demonstrate the proposed approach can boost the performances steadily and achieve the state-of-the-art performance for both zero-shot classification and zero-shot retrieval.

##### Abstract (translated by Google)
零射击学习（ZSL）的典型流程是将视觉特征和类语义描述符用线性或双线性模型整合到多模式框架中。然而，视觉特征和类语义描述符位于不同的结构空间，线性或双线性模型不能很好地捕捉不同模态之间的语义交互。在这封信中，我们提出了一种非线性的方法，通过将语义描述符嵌入到多类分类网络的softmax层中，通过语义Softmax丢失将ZSL强加为多类分类问题。为了缩小视觉特征和语义描述符之间的结构差异，我们进一步使用L2归一化约束来重建与语义描述符重建的视觉特征和视觉原型之间的差异。在三个基准数据集（即AwA，CUB和SUN）上的结果表明，所提出的方法可稳定地提高性能，并实现零炮分类和零炮检索的最新性能。

##### URL
[https://arxiv.org/abs/1705.07692](https://arxiv.org/abs/1705.07692)

##### PDF
[https://arxiv.org/pdf/1705.07692](https://arxiv.org/pdf/1705.07692)

