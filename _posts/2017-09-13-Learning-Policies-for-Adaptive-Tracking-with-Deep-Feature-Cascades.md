---
layout: post
title: "Learning Policies for Adaptive Tracking with Deep Feature Cascades"
date: 2017-09-13 19:39:45
categories: arXiv_CV
tags: arXiv_CV Tracking Reinforcement_Learning Object_Tracking Relation
author: Chen Huang, Simon Lucey, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
Visual object tracking is a fundamental and time-critical vision task. Recent years have seen many shallow tracking methods based on real-time pixel-based correlation filters, as well as deep methods that have top performance but need a high-end GPU. In this paper, we learn to improve the speed of deep trackers without losing accuracy. Our fundamental insight is to take an adaptive approach, where easy frames are processed with cheap features (such as pixel values), while challenging frames are processed with invariant but expensive deep features. We formulate the adaptive tracking problem as a decision-making process, and learn an agent to decide whether to locate objects with high confidence on an early layer, or continue processing subsequent layers of a network. This significantly reduces the feed-forward cost for easy frames with distinct or slow-moving objects. We train the agent offline in a reinforcement learning fashion, and further demonstrate that learning all deep layers (so as to provide good features for adaptive tracking) can lead to near real-time average tracking speed of 23 fps on a single CPU while achieving state-of-the-art performance. Perhaps most tellingly, our approach provides a 100X speedup for almost 50% of the time, indicating the power of an adaptive approach.

##### Abstract (translated by Google)
视觉对象跟踪是一项基本和时间关键的视觉任务。近年来，已经有许多基于实时像素相关滤波器的浅层跟踪方法，以及具有最高性能但需要高端GPU的深层方法。在本文中，我们学习如何提高深度跟踪器的速度而不会失去准确性。我们的基本洞察是采取自适应方法，在这种方法中简单的帧用廉价的特征（如像素值）进行处理，而具有挑战性的帧则用不变但昂贵的深度特征进行处理。我们将自适应跟踪问题作为一个决策过程来制定，并学习一个代理来决定是否在早期阶段高可信地定位对象，或者继续处理网络的后续层。这显着降低了具有不同或缓慢移动对象的简单帧的前馈成本。我们以强化学习的方式离线训练代理，并且进一步证明学习所有深层（以便为自适应跟踪提供良好的特征）可以导致在实现状态的同时在单个CPU上接近实时平均跟踪速度为23fps最先进的性能。也许最具有说服力的是，我们的方法几乎可以在50％的时间内提供100倍的加速，说明自适应方法的强大功能。

##### URL
[https://arxiv.org/abs/1708.02973](https://arxiv.org/abs/1708.02973)

##### PDF
[https://arxiv.org/pdf/1708.02973](https://arxiv.org/pdf/1708.02973)

