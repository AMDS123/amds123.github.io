---
layout: post
title: "Online and Offline Handwritten Chinese Character Recognition: A Comprehensive Study and New Benchmark"
date: 2016-06-18 14:49:32
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Deep_Learning Recognition
author: Xu-Yao Zhang, Yoshua Bengio, Cheng-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep learning based methods have achieved the state-of-the-art performance for handwritten Chinese character recognition (HCCR) by learning discriminative representations directly from raw data. Nevertheless, we believe that the long-and-well investigated domain-specific knowledge should still help to boost the performance of HCCR. By integrating the traditional normalization-cooperated direction-decomposed feature map (directMap) with the deep convolutional neural network (convNet), we are able to obtain new highest accuracies for both online and offline HCCR on the ICDAR-2013 competition database. With this new framework, we can eliminate the needs for data augmentation and model ensemble, which are widely used in other systems to achieve their best results. This makes our framework to be efficient and effective for both training and testing. Furthermore, although directMap+convNet can achieve the best results and surpass human-level performance, we show that writer adaptation in this case is still effective. A new adaptation layer is proposed to reduce the mismatch between training and test data on a particular source layer. The adaptation process can be efficiently and effectively implemented in an unsupervised manner. By adding the adaptation layer into the pre-trained convNet, it can adapt to the new handwriting styles of particular writers, and the recognition accuracy can be further improved consistently and significantly. This paper gives an overview and comparison of recent deep learning based approaches for HCCR, and also sets new benchmarks for both online and offline HCCR.

##### Abstract (translated by Google)
最近的基于深度学习的方法通过直接从原始数据中学习歧视性表示来实现手写汉字识别（HCCR）的最新性能。尽管如此，我们认为长期以来深入研究的领域特定知识仍然有助于提高HCCR的性能。通过将传统的归一化协作方向分解特征图（directMap）与深度卷积神经网络（convNet）相结合，我们能够在ICDAR-2013竞争数据库上获得线上和线下HCCR的最高精度。有了这个新的框架，我们可以消除数据增强和模型集成的需求，这些集成在其他系统中被广泛使用，以取得最好的结果。这使得我们的框架在培训和测试方面都是高效和有效的。而且，虽然directMap + convNet能够取得最好的效果，并且超越了人类的表现，但是这种情况下的作者适应仍然是有效的。提出了一种新的适应层来减少特定源层上的训练和测试数据之间的不匹配。适应过程可以以无监督的方式高效和有效地实施。通过在预训练的convNet中增加适配层，可以适应特定作者的新手写风格，识别准确性可以进一步提高，并且有显着的提高。本文对HCCR最近的深度学习方法进行了概述和比较，并为在线和离线的HCCR提供了新的基准。

##### URL
[https://arxiv.org/abs/1606.05763](https://arxiv.org/abs/1606.05763)

##### PDF
[https://arxiv.org/pdf/1606.05763](https://arxiv.org/pdf/1606.05763)

