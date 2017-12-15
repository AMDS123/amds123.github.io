---
layout: post
title: "Self-taught learning of a deep invariant representation for visual tracking via temporal slowness principle"
date: 2016-04-14 13:12:07
categories: arXiv_CV
tags: arXiv_CV Tracking CNN
author: Jason Kuen, Kian Ming Lim, Chin Poo Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Visual representation is crucial for a visual tracking method's performances. Conventionally, visual representations adopted in visual tracking rely on hand-crafted computer vision descriptors. These descriptors were developed generically without considering tracking-specific information. In this paper, we propose to learn complex-valued invariant representations from tracked sequential image patches, via strong temporal slowness constraint and stacked convolutional autoencoders. The deep slow local representations are learned offline on unlabeled data and transferred to the observational model of our proposed tracker. The proposed observational model retains old training samples to alleviate drift, and collect negative samples which are coherent with target's motion pattern for better discriminative tracking. With the learned representation and online training samples, a logistic regression classifier is adopted to distinguish target from background, and retrained online to adapt to appearance changes. Subsequently, the observational model is integrated into a particle filter framework to peform visual tracking. Experimental results on various challenging benchmark sequences demonstrate that the proposed tracker performs favourably against several state-of-the-art trackers.

##### Abstract (translated by Google)
视觉表示对视觉追踪方法的性能至关重要。传统上，视觉追踪中采用的视觉表示依赖手工制作的计算机视觉描述符。这些描述符通常是在没有考虑跟踪特定信息的情况下开发的。在本文中，我们提出通过强时间慢度约束和叠层卷积自动编码器，从被跟踪的序列图像块中学习复值不变表示。深入慢速的局部表征是在未标记的数据下离线学习，并转移到我们提出的跟踪器的观测模型。建议的观测模型保留旧的训练样本以减轻漂移，收集与目标运动模式相一致的负样本，以便更好地进行判别性跟踪。通过学习表征和在线训练样本，采用逻辑回归分类器来区分目标和背景，并在线重新训练以适应外观变化。随后，将观测模型整合到粒子滤波框架中，进行视觉跟踪。各种具有挑战性的基准测试序列的实验结果表明，所提出的跟踪器对于多个最先进的跟踪器性能良好。

##### URL
[https://arxiv.org/abs/1604.04144](https://arxiv.org/abs/1604.04144)

##### PDF
[https://arxiv.org/pdf/1604.04144](https://arxiv.org/pdf/1604.04144)

