---
layout: post
title: "SphereFace: Deep Hypersphere Embedding for Face Recognition"
date: 2017-11-17 21:55:51
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN Quantitative Recognition Face_Recognition
author: Weiyang Liu, Yandong Wen, Zhiding Yu, Ming Li, Bhiksha Raj, Le Song
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses deep face recognition (FR) problem under open-set protocol, where ideal face features are expected to have smaller maximal intra-class distance than minimal inter-class distance under a suitably chosen metric space. However, few existing algorithms can effectively achieve this criterion. To this end, we propose the angular softmax (A-Softmax) loss that enables convolutional neural networks (CNNs) to learn angularly discriminative features. Geometrically, A-Softmax loss can be viewed as imposing discriminative constraints on a hypersphere manifold, which intrinsically matches the prior that faces also lie on a manifold. Moreover, the size of angular margin can be quantitatively adjusted by a parameter $m$. We further derive specific $m$ to approximate the ideal feature criterion. Extensive analysis and experiments on Labeled Face in the Wild (LFW), Youtube Faces (YTF) and MegaFace Challenge show the superiority of A-Softmax loss in FR tasks. The code has also been made publicly available.

##### Abstract (translated by Google)
本文针对开放协议下的深度人脸识别（FR）问题，理想的人脸特征在适当选择的度量空间下，最小的类内距离比最小的类间距离要小。但是，现有的算法很少能有效地达到这个标准。为此，我们提出角度softmax（A-Softmax）损失，使卷积神经网络（CNN）能够学习角度判别特征。在几何学上，A-Softmax损失可以被看作是在超球面流形上施加有区别的约束，其本质上与之前面对的也存在于流形上。此外，角边界的大小可以通过参数$ m $进行定量调整。我们进一步推导出特定的$ m $来近似理想的特征标准。在野外贴标人脸（LFW），Youtube FACE（YTF）和MegaFace挑战中进行了大量的分析和实验，显示了A-Softmax在FR任务中的优势。该代码也已公开发布。

##### URL
[https://arxiv.org/abs/1704.08063](https://arxiv.org/abs/1704.08063)

##### PDF
[https://arxiv.org/pdf/1704.08063](https://arxiv.org/pdf/1704.08063)

