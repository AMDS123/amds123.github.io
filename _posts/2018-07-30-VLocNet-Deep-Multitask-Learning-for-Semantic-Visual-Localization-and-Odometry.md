---
layout: post
title: "VLocNet++: Deep Multitask Learning for Semantic Visual Localization and Odometry"
date: 2018-07-30 10:35:48
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Embedding Deep_Learning Relation
author: Noha Radwan, Abhinav Valada, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic understanding and localization are fundamental enablers of robot autonomy that have for the most part been tackled as disjoint problems. While deep learning has enabled recent breakthroughs across a wide spectrum of scene understanding tasks, its applicability to state estimation tasks has been limited due to the direct formulation that renders it incapable of encoding scene-specific constrains. In this work, we propose the VLocNet++ architecture that employs a multitask learning approach to exploit the inter-task relationship between learning semantics, regressing 6-DoF global pose and odometry, for the mutual benefit of each of these tasks. Our network overcomes the aforementioned limitation by simultaneously embedding geometric and semantic knowledge of the world into the pose regression network. We propose a novel adaptive weighted fusion layer to aggregate motion-specific temporal information and to fuse semantic features into the localization stream based on region activations. Furthermore, we propose a self-supervised warping technique that uses the relative motion to warp intermediate network representations in the segmentation stream for learning consistent semantics. Finally, we introduce a first-of-a-kind urban outdoor localization dataset with pixel-level semantic labels and multiple loops for training deep networks. Extensive experiments on the challenging Microsoft 7-Scenes benchmark and our DeepLoc dataset demonstrate that our approach exceeds the state-of-the-art outperforming local feature-based methods while simultaneously performing multiple tasks and exhibiting substantial robustness in challenging scenarios.

##### Abstract (translated by Google)
语义理解和本地化是机器人自治的基本推动因素，它们在很大程度上被解决为不相交的问题。虽然深度学习已经在最广泛的场景理解任务中实现了最近的突破，但是由于直接公式使其无法编码特定于场景的约束，因此其对状态估计任务的适用性受到限制。在这项工作中，我们提出了VLocNet ++架构，该架构采用多任务学习方法来利用学习语义之间的任务间关系，回归6-DoF全局姿势和里程计，以实现这些任务的互利。我们的网络通过同时将世界的几何和语义知识嵌入到姿势回归网络中来克服上述限制。我们提出了一种新颖的自适应加权融合层，用于聚合特定于运动的时间信息，并基于区域激活将语义特征融合到本地化流中。此外，我们提出了一种自我监督的变形技术，该技术使用相对运动来扭曲分段流中的中间网络表示，以学习一致的语义。最后，我们介绍了第一种城市户外本地化数据集，其中包含像素级语义标签和多个循环，用于训练深层网络。针对具有挑战性的Microsoft 7-Scenes基准测试和DeepLo​​c数据集的大量实验表明，我们的方法超越了最先进的基于本地特征的方法，同时执行多项任务并在具有挑战性的场景中展现出强大的稳健性。

##### URL
[http://arxiv.org/abs/1804.08366](http://arxiv.org/abs/1804.08366)

##### PDF
[http://arxiv.org/pdf/1804.08366](http://arxiv.org/pdf/1804.08366)

