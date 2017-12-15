---
layout: post
title: "Learning Image Matching by Simply Watching Video"
date: 2016-03-29 04:35:49
categories: arXiv_CV
tags: arXiv_CV CNN
author: Gucan Long, Laurent Kneip, Jose M. Alvarez, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents an unsupervised learning based approach to the ubiquitous computer vision problem of image matching. We start from the insight that the problem of frame-interpolation implicitly solves for inter-frame correspondences. This permits the application of analysis-by-synthesis: we firstly train and apply a Convolutional Neural Network for frame-interpolation, then obtain correspondences by inverting the learned CNN. The key benefit behind this strategy is that the CNN for frame-interpolation can be trained in an unsupervised manner by exploiting the temporal coherency that is naturally contained in real-world video sequences. The present model therefore learns image matching by simply watching videos. Besides a promise to be more generally applicable, the presented approach achieves surprising performance comparable to traditional empirically designed methods.

##### Abstract (translated by Google)
这项工作提出了一个无监督的学习为基础的方法，无处不在的计算机视觉问题的图像匹配。我们从洞察到，帧内插问题隐含地解决了帧间对应的问题。这允许应用综合分析：我们首先训练并应用卷积神经网络进行帧插值，然后通过反演学习的CNN来获得对应关系。这种策略背后的关键好处是，帧内插的CNN可以通过利用现实视频序列中自然包含的时间一致性以无监督的方式进行训练。因此，本模型通过简单地观看视频来学习图像匹配。除了承诺更普遍适用之外，所提出的方法实现了与传统的经验设计方法相媲美的令人惊讶的性能。

##### URL
[https://arxiv.org/abs/1603.06041](https://arxiv.org/abs/1603.06041)

##### PDF
[https://arxiv.org/pdf/1603.06041](https://arxiv.org/pdf/1603.06041)

