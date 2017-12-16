---
layout: post
title: "Transferring Object-Scene Convolutional Neural Networks for Event Recognition in Still Images"
date: 2016-09-01 09:47:22
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Relation Recognition
author: Limin Wang, Zhe Wang, Yu Qiao, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Event recognition in still images is an intriguing problem and has potential for real applications. This paper addresses the problem of event recognition by proposing a convolutional neural network that exploits knowledge of objects and scenes for event classification (OS2E-CNN). Intuitively, it stands to reason that there exists a correlation among the concepts of objects, scenes, and events. We empirically demonstrate that the recognition of objects and scenes substantially contributes to the recognition of events. Meanwhile, we propose an iterative selection method to identify a subset of object and scene classes, which help to more efficiently and effectively transfer their deep representations to event recognition. Specifically, we develop three types of transferring techniques: (1) initialization-based transferring, (2) knowledge-based transferring, and (3) data-based transferring. These newly designed transferring techniques exploit multi-task learning frameworks to incorporate extra knowledge from other networks and additional datasets into the training procedure of event CNNs. These multi-task learning frameworks turn out to be effective in reducing the effect of over-fitting and improving the generalization ability of the learned CNNs. With OS2E-CNN, we design a multi-ratio and multi-scale cropping strategy, and propose an end-to-end event recognition pipeline. We perform experiments on three event recognition benchmarks: the ChaLearn Cultural Event Recognition dataset, the Web Image Dataset for Event Recognition (WIDER), and the UIUC Sports Event dataset. The experimental results show that our proposed algorithm successfully adapts object and scene representations towards the event dataset and that it achieves the current state-of-the-art performance on these challenging datasets.

##### Abstract (translated by Google)
静止图像中的事件识别是一个有趣的问题，具有实际应用的潜力。本文针对事件识别问题提出了一种卷积神经网络，利用物体和场景的知识进行事件分类（OS2E-CNN）。直观地说，在对象，场景和事件的概念之间存在相关性。我们凭经验证明，物体和场景的识别对事件的识别有实质性的贡献。同时，我们提出了迭代选择方法来识别对象和场景类别的一个子集，这有助于更高效和有效地将其深度表示转移到事件识别。具体来说，我们开发了三种转移技术：（1）基于初始化的转移，（2）基于知识的转移，（3）基于数据的转移。这些新设计的传输技术利用多任务学习框架将来自其他网络的额外知识和附加数据集合到事件CNN的训练过程中。这些多任务学习框架在减少过度拟合和提高学习CNN的泛化能力方面起到了有效的作用。利用OS2E-CNN，我们设计了一个多比例多尺度裁剪策略，并提出了一个端到端的事件识别流水线。我们在三个事件识别基准上进行实验：ChaLearn文化事件识别数据集，事件识别的Web图像数据集（WIDER）和UIUC运动事件数据集。实验结果表明，我们提出的算法成功地适应对象和场景表示对事件数据集，并在这些具有挑战性的数据集上实现当前最先进的性能。

##### URL
[https://arxiv.org/abs/1609.00162](https://arxiv.org/abs/1609.00162)

##### PDF
[https://arxiv.org/pdf/1609.00162](https://arxiv.org/pdf/1609.00162)

