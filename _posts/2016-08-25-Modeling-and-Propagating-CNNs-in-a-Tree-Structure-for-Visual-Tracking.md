---
layout: post
title: "Modeling and Propagating CNNs in a Tree Structure for Visual Tracking"
date: 2016-08-25 18:29:53
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking
author: Hyeonseob Nam, Mooyeol Baek, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We present an online visual tracking algorithm by managing multiple target appearance models in a tree structure. The proposed algorithm employs Convolutional Neural Networks (CNNs) to represent target appearances, where multiple CNNs collaborate to estimate target states and determine the desirable paths for online model updates in the tree. By maintaining multiple CNNs in diverse branches of tree structure, it is convenient to deal with multi-modality in target appearances and preserve model reliability through smooth updates along tree paths. Since multiple CNNs share all parameters in convolutional layers, it takes advantage of multiple models with little extra cost by saving memory space and avoiding redundant network evaluations. The final target state is estimated by sampling target candidates around the state in the previous frame and identifying the best sample in terms of a weighted average score from a set of active CNNs. Our algorithm illustrates outstanding performance compared to the state-of-the-art techniques in challenging datasets such as online tracking benchmark and visual object tracking challenge.

##### Abstract (translated by Google)
我们提出了一个在线视觉跟踪算法，通过管理树形结构中的多个目标外观模型。该算法采用卷积神经网络（CNN）来表示目标外观，其中多个CNN协作估计目标状态并确定树中在线模型更新的期望路径。通过在树形结构的不同分支上维护多个CNN，可以方便地处理目标表面的多模态，并通过沿着树形路径平滑更新来保持模型的可靠性。由于多个CNN共享卷积层中的所有参数，因此通过节省存储器空间并避免冗余网络评估而利用了多个模型，而额外成本很少。最终的目标状态通过对前一帧中的状态周围的目标候选进行采样并且根据来自一组活动CNN的加权平均分来识别最佳样本来估计。我们的算法与具有挑战性的数据集（如在线跟踪基准和视觉对象跟踪挑战）中的最新技术相比，表现出色。

##### URL
[https://arxiv.org/abs/1608.07242](https://arxiv.org/abs/1608.07242)

##### PDF
[https://arxiv.org/pdf/1608.07242](https://arxiv.org/pdf/1608.07242)

