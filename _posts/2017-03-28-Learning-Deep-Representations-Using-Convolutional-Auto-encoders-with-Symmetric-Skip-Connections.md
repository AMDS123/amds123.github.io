---
layout: post
title: "Learning Deep Representations Using Convolutional Auto-encoders with Symmetric Skip Connections"
date: 2017-03-28 14:49:42
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification
author: Jianfeng Dong, Xiao-Jiao Mao, Chunhua Shen, Yu-Bin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised pre-training was a critical technique for training deep neural networks years ago. With sufficient labeled data and modern training techniques, it is possible to train very deep neural networks from scratch in a purely supervised manner nowadays. However, unlabeled data is easier to obtain and usually of very large scale. How to make use of them better to help supervised learning is still a well-valued topic. In this paper, we investigate convolutional denoising auto-encoders to show that unsupervised pre-training can still improve the performance of high-level image related tasks such as image classification and semantic segmentation. The architecture we use is a convolutional auto-encoder network with symmetric shortcut connections. We empirically show that symmetric shortcut connections are very important for learning abstract representations via image reconstruction. When no extra unlabeled data are available, unsupervised pre-training with our network can regularize the supervised training and therefore lead to better generalization performance. With the help of unsupervised pre-training, our method achieves very competitive results in image classification using very simple all-convolution networks. When labeled data are limited but extra unlabeled data are available, our method achieves good results in several semi-supervised learning tasks.

##### Abstract (translated by Google)
无监督的预训练是多年前训练深度神经网络的关键技术。有了足够的标记数据和现代的训练技术，现在可以从纯粹的监督的方式从头开始训练非常深的神经网络。然而，无标签的数据更容易获得，通常规模非常大。如何更好地利用它们来帮助监督学习仍然是一个非常有价值的话题。在本文中，我们研究了卷积去噪自动编码器，表明无监督预训练仍然可以提高图像分类和语义分割等高级图像相关任务的性能。我们使用的架构是具有对称快捷连接的卷积自动编码器网络。我们经验地表明，对称快捷连接对于通过图像重构来学习抽象表示非常重要。当没有额外的未标记数据可用时，无监督的预训练与我们的网络可以规范监督训练，从而导致更好的泛化性能。在无监督预训练的帮助下，我们的方法在使用非常简单的全卷积网络的图像分类方面取得了非常有竞争力的结果。当标记的数据是有限的，但额外的未标记的数据可用，我们的方法在几个半监督学习任务取得了良好的效果。

##### URL
[https://arxiv.org/abs/1611.09119](https://arxiv.org/abs/1611.09119)

##### PDF
[https://arxiv.org/pdf/1611.09119](https://arxiv.org/pdf/1611.09119)

