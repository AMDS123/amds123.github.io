---
layout: post
title: "Modality Distillation with Multiple Stream Networks for Action Recognition"
date: 2018-06-19 08:56:13
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Recognition
author: Nuno Garcia, Pietro Morerio, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
Diverse input data modalities can provide complementary cues for several tasks, usually leading to more robust algorithms and better performance. However, while a (training) dataset could be accurately designed to include a variety of sensory inputs, it is often the case that not all modalities could be available in real life (testing) scenarios, where a model has to be deployed. This raises the challenge of how to learn robust representations leveraging multimodal data in the training stage, while considering limitations at test time, such as noisy or missing modalities. 
 This paper presents a new approach for multimodal video action recognition, developed within the unified frameworks of distillation and privileged information, named generalized distillation. Particularly, we consider the case of learning representations from depth and RGB videos, while relying on RGB data only at test time. We propose a new approach to train an hallucination network that learns to distill depth features through multiplicative connections of spatiotemporal representations, leveraging soft labels and hard labels, as well as distance between feature maps. We report state-of-the-art results on video action classification on the largest multimodal dataset available for this task, the NTU RGB+D.

##### Abstract (translated by Google)
多样化的输入数据模式可以为多项任务提供互补的线索，通常会导致更强大的算法和更好的性能。然而，尽管可以精确设计（训练）数据集以包括各种感官输入，但是在实际生活（测试）场景中并非所有模式都可用，其中必须部署模型。这提出了如何在训练阶段学习利用多模态数据的鲁棒表示的挑战，同时考虑到测试时间的限制，例如嘈杂或缺少模态。
 本文提出了一种多模式视频动作识别的新方法，该方法在统一的蒸馏和特权信息框架内开发，称为广义蒸馏。特别是，我们考虑从深度和RGB视频学习表示，而仅在测试时间依赖RGB数据。我们提出了一种新的方法来训练一个幻觉网络，学习通过时空表示的乘法连接来提取深度特征，利用软标签和硬标签以及特征映射之间的距离。我们在可用于此任务的最大多模式数据集NTU RGB + D上报告关于视频动作分类的最新结果。

##### URL
[http://arxiv.org/abs/1806.07110](http://arxiv.org/abs/1806.07110)

##### PDF
[http://arxiv.org/pdf/1806.07110](http://arxiv.org/pdf/1806.07110)

