---
layout: post
title: "StarMap for Category-Agnostic Keypoint and Viewpoint Estimation"
date: 2018-03-25 20:28:53
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Detection
author: Xingyi Zhou, Arjun Karpur, Linjie Luo, Qixing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic keypoints provide concise abstractions for a variety of visual understanding tasks. Existing methods define semantic keypoints separately for each category with a fixed number of semantic labels. As a result, these representation is not suitable when objects have a varying number of parts, e.g. chairs with varying number of legs. We propose a category-agnostic keypoint representation encoded with their 3D locations in the canonical object views. Our intuition is that the 3D locations of the keypoints in canonical object views contain rich semantic and compositional information. Our representation thus consists of a single channel, multi-peak heatmap (StarMap) for all the keypoints and their corresponding features as 3D locations in the canonical object view (CanViewFeature) defined for each category. Not only is our representation flexible, but we also demonstrate competitive performance in keypoint detection and localization compared to category-specific state-of-the-art methods. Additionally, we show that when augmented with an additional depth channel (DepthMap) to lift the 2D keypoints to 3D, our representation can achieve state-of-the-art results in viewpoint estimation. Finally, we demonstrate that each individual component of our framework can be used on the task of human pose estimation to simplify the state-of-the-art architecture.

##### Abstract (translated by Google)
语义关键点为各种视觉理解任务提供简洁的抽象。现有方法为每个类别分别定义语义关键点，并使用固定数量的语义标签。结果，当物体具有不同数量的部件时，这些表示是不合适的，例如，椅子的腿数不一。我们建议在规范对象视图中使用3D位置编码与类别无关的关键点表示。我们的直觉是，规范对象视图中关键点的3D位置包含丰富的语义和组合信息。因此，我们的表示包含所有关键点的单通道，多峰值热图（StarMap）及其对应特征，作为为每个类别定义的规范对象视图（CanViewFeature）中的3D位置。我们的代表不仅灵活多变，而且与特定类别的最先进方法相比，我们还在关键点检测和本地化方面展现出具有竞争力的性能。此外，我们还表明，当增加一个额外的深度通道（DepthMap）以将2D关键点提升到3D时，我们的表示可以实现视点估计中的最新结果。最后，我们证明我们框架中的每个单独组件都可用于人体姿态估计的任务，以简化最先进的体系结构。

##### URL
[https://arxiv.org/abs/1803.09331](https://arxiv.org/abs/1803.09331)

##### PDF
[https://arxiv.org/pdf/1803.09331](https://arxiv.org/pdf/1803.09331)

