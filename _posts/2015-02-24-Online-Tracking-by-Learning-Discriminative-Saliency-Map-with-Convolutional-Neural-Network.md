---
layout: post
title: "Online Tracking by Learning Discriminative Saliency Map with Convolutional Neural Network"
date: 2015-02-24 13:10:32
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Tracking CNN Recognition
author: Seunghoon Hong, Tackgeun You, Suha Kwak, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an online visual tracking algorithm by learning discriminative saliency map using Convolutional Neural Network (CNN). Given a CNN pre-trained on a large-scale image repository in offline, our algorithm takes outputs from hidden layers of the network as feature descriptors since they show excellent representation performance in various general visual recognition problems. The features are used to learn discriminative target appearance models using an online Support Vector Machine (SVM). In addition, we construct target-specific saliency map by backpropagating CNN features with guidance of the SVM, and obtain the final tracking result in each frame based on the appearance model generatively constructed with the saliency map. Since the saliency map visualizes spatial configuration of target effectively, it improves target localization accuracy and enable us to achieve pixel-level target segmentation. We verify the effectiveness of our tracking algorithm through extensive experiment on a challenging benchmark, where our method illustrates outstanding performance compared to the state-of-the-art tracking algorithms.

##### Abstract (translated by Google)
我们通过使用卷积神经网络（CNN）学习辨识显着图提出一种在线视觉跟踪算法。给定一个离线大规模图像库预先训练的CNN算法，该算法将网络隐层的输出作为特征描述子，因为它们在各种一般的视觉识别问题中表现出优秀的表现性能。这些特征用于使用在线支持向量机（SVM）学习辨别目标外观模型。另外，在支持向量机的引导下，通过反向传播CNN特征构造目标特定的显着图，并根据显着图生成的外观模型，得到各帧的最终跟踪结果。由于显着图有效地显示了目标的空间配置，提高了目标的定位精度，使我们能够实现像素级的目标分割。我们通过对具有挑战性的基准进行广泛的实验来验证我们的跟踪算法的有效性，其中我们的方法与最先进的跟踪算法相比表现出优异的性能。

##### URL
[https://arxiv.org/abs/1502.06796](https://arxiv.org/abs/1502.06796)

##### PDF
[https://arxiv.org/pdf/1502.06796](https://arxiv.org/pdf/1502.06796)

