---
layout: post
title: "Deep Person Re-Identification with Improved Embedding and Efficient Training"
date: 2017-07-08 11:05:17
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding CNN
author: Haibo Jin, Xiaobo Wang, Shengcai Liao, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification task has been greatly boosted by deep convolutional neural networks (CNNs) in recent years. The core of which is to enlarge the inter-class distinction as well as reduce the intra-class variance. However, to achieve this, existing deep models prefer to adopt image pairs or triplets to form verification loss, which is inefficient and unstable since the number of training pairs or triplets grows rapidly as the number of training data grows. Moreover, their performance is limited since they ignore the fact that different dimension of embedding may play different importance. In this paper, we propose to employ identification loss with center loss to train a deep model for person re-identification. The training process is efficient since it does not require image pairs or triplets for training while the inter-class distinction and intra-class variance are well handled. To boost the performance, a new feature reweighting (FRW) layer is designed to explicitly emphasize the importance of each embedding dimension, thus leading to an improved embedding. Experiments on several benchmark datasets have shown the superiority of our method over the state-of-the-art alternatives on both accuracy and speed.

##### Abstract (translated by Google)
深度卷积神经网络（CNNs）近年来大大提高了人的再识别任务。其核心是扩大阶层差异，减少阶层差异。然而，为了实现这一点，现有的深度模型更倾向于采用图像对或三元组来形成验证丢失，这是因为训练数据的增长，训练对或三元组的数量迅速增长，因此效率低下且不稳定。而且，由于他们忽视嵌入的不同维度可能具有不同重要性的事实，所以它们的性能是有限的。在本文中，我们建议使用带有中心损失的识别损失来训练人员重新识别的深层模型。训练过程是高效的，因为它不需要图像对或三联训练，而类间差异和类内差异得到很好的处理。为了提高性能，设计了一个新的特征重新加权（FRW）层来明确强调每个嵌入维度的重要性，从而导致改进的嵌入。在几个基准数据集上的实验已经证明了我们的方法在精度和速度上优于最先进的替代方法。

##### URL
[https://arxiv.org/abs/1705.03332](https://arxiv.org/abs/1705.03332)

##### PDF
[https://arxiv.org/pdf/1705.03332](https://arxiv.org/pdf/1705.03332)

