---
layout: post
title: "Low-Cost Scene Modeling using a Density Function Improves Segmentation Performance"
date: 2016-05-26 22:34:37
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Relation
author: Vivek Sharma, Sule Yildirim-Yayilgan, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a low cost and effective way to combine a free simulation software and free CAD models for modeling human-object interaction in order to improve human & object segmentation. It is intended for research scenarios related to safe human-robot collaboration (SHRC) and interaction (SHRI) in the industrial domain. The task of human and object modeling has been used for detecting activity, and for inferring and predicting actions, different from those works, we do human and object modeling in order to learn interactions in RGB-D data for improving segmentation. For this purpose, we define a novel density function to model a three dimensional (3D) scene in a virtual environment (VREP). This density function takes into account various possible configurations of human-object and object-object relationships and interactions governed by their affordances. Using this function, we synthesize a large, realistic and highly varied synthetic RGB-D dataset that we use for training. We train a random forest classifier, and the pixelwise predictions obtained is integrated as a unary term in a pairwise conditional random fields (CRF). Our evaluation shows that modeling these interactions improves segmentation performance by ~7\% in mean average precision and recall over state-of-the-art methods that ignore these interactions in real-world data. Our approach is computationally efficient, robust and can run real-time on consumer hardware.

##### Abstract (translated by Google)
我们提出了一个低成本和有效的方法来结合免费的模拟软件和免费的CAD模型来建模人 - 对象交互，以改善人与物体的分割。它旨在用于与工业领域中的安全的人机器人协作（SHRC）和交互（SHRI）相关的研究场景。人类和对象建模的任务已经被用于检测活动，并且为了推断和预测与这些工作不同的行为，我们进行人体和对象建模以学习RGB-D数据中的交互以改善分割。为此，我们定义了一个新的密度函数来模拟虚拟环境（VREP）中的三维（3D）场景。这个密度函数考虑了人对象和对象 - 对象之间的各种可能的配置关系以及由它们的可供性决定的交互作用。使用这个功能，我们合成了一个大的，逼真的，高度多样化的合成RGB-D数据集，我们用于训练。我们训练一个随机的森林分类器，并且所获得的像素预测被整合成一对条件随机场（CRF）中的单项。我们的评估表明，对这些交互进行建模可以使平均平均精度的分割性能提高〜7％，并且可以忽略现实世界中忽略这些相互作用的最新方法。我们的方法计算效率高，可靠，可以在消费者硬件上实时运行。

##### URL
[https://arxiv.org/abs/1605.08464](https://arxiv.org/abs/1605.08464)

##### PDF
[https://arxiv.org/pdf/1605.08464](https://arxiv.org/pdf/1605.08464)

