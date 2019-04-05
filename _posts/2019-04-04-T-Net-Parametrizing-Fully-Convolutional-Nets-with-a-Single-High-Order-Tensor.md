---
layout: post
title: "T-Net: Parametrizing Fully Convolutional Nets with a Single High-Order Tensor"
date: 2019-04-04 17:55:37
categories: arXiv_AI
tags: arXiv_AI Regularization Pose_Estimation CNN
author: Jean Kossaifi, Adrian Bulat, Georgios Tzimiropoulos, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Recent findings indicate that over-parametrization, while crucial for successfully training deep neural networks, also introduces large amounts of redundancy. Tensor methods have the potential to efficiently parametrize over-complete representations by leveraging this redundancy. In this paper, we propose to fully parametrize Convolutional Neural Networks (CNNs) with a single high-order, low-rank tensor. Previous works on network tensorization have focused on parametrizing individual layers (convolutional or fully connected) only, and perform the tensorization layer-by-layer separately. In contrast, we propose to jointly capture the full structure of a neural network by parametrizing it with a single high-order tensor, the modes of which represent each of the architectural design parameters of the network (e.g. number of convolutional blocks, depth, number of stacks, input features, etc). This parametrization allows to regularize the whole network and drastically reduce the number of parameters. Our model is end-to-end trainable and the low-rank structure imposed on the weight tensor acts as an implicit regularization. We study the case of networks with rich structure, namely Fully Convolutional Networks (FCNs), which we propose to parametrize with a single 8th-order tensor. We show that our approach can achieve superior performance with small compression rates, and attain high compression rates with negligible drop in accuracy for the challenging task of human pose estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02698](http://arxiv.org/abs/1904.02698)

##### PDF
[http://arxiv.org/pdf/1904.02698](http://arxiv.org/pdf/1904.02698)

