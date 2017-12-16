---
layout: post
title: "Saliency-guided video classification via adaptively weighted learning"
date: 2017-03-26 02:43:13
categories: arXiv_CV
tags: arXiv_CV Salient Video_Classification Classification Deep_Learning
author: Yunzhen Zhao, Yuxin Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Video classification is productive in many practical applications, and the recent deep learning has greatly improved its accuracy. However, existing works often model video frames indiscriminately, but from the view of motion, video frames can be decomposed into salient and non-salient areas naturally. Salient and non-salient areas should be modeled with different networks, for the former present both appearance and motion information, and the latter present static background information. To address this problem, in this paper, video saliency is predicted by optical flow without supervision firstly. Then two streams of 3D CNN are trained individually for raw frames and optical flow on salient areas, and another 2D CNN is trained for raw frames on non-salient areas. For the reason that these three streams play different roles for each class, the weights of each stream are adaptively learned for each class. Experimental results show that saliency-guided modeling and adaptively weighted learning can reinforce each other, and we achieve the state-of-the-art results.

##### Abstract (translated by Google)
视频分类在许多实际应用中是有生产力的，最近的深度学习大大提高了它的准确性。然而，现有的作品往往不加区分地对视频帧进行建模，但从运动的角度来看，视频帧自然可以分解为显着的和非显着的区域。显着区域和非显着区域应该用不同的网络来模拟，前者呈现出动态信息，后者呈现静态背景信息。为了解决这个问题，本文首先利用光流预测视频显着性。然后，两个3D CNN流分别被训练用于原始帧和显着区域上的光流，另一个2D CNN被训练用于非显着区域上的原始帧。由于这三个流在每个类中扮演着不同的角色，因此每个类的权重都是自适应学习的。实验结果表明，显着性引导建模和自适应加权学习可以相互加强，我们达到了最新的结果。

##### URL
[https://arxiv.org/abs/1703.08025](https://arxiv.org/abs/1703.08025)

##### PDF
[https://arxiv.org/pdf/1703.08025](https://arxiv.org/pdf/1703.08025)

