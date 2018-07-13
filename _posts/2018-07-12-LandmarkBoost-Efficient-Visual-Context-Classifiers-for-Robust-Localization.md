---
layout: post
title: "LandmarkBoost: Efficient Visual Context Classifiers for Robust Localization"
date: 2018-07-12 16:14:37
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Marcin Dymczyk, Igor Gilitschenski, Juan Nieto, Simon Lynen, Bernhard Zeisl, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
The growing popularity of autonomous systems creates a need for reliable and efficient metric pose retrieval algorithms. Currently used approaches tend to rely on nearest neighbor search of binary descriptors to perform the 2D-3D matching and guarantee realtime capabilities on mobile platforms. These methods struggle, however, with the growing size of the map, changes in viewpoint or appearance, and visual aliasing present in the environment. The rigidly defined descriptor patterns only capture a limited neighborhood of the keypoint and completely ignore the overall visual context. 
 We propose LandmarkBoost - an approach that, in contrast to the conventional 2D-3D matching methods, casts the search problem as a landmark classification task. We use a boosted classifier to classify landmark observations and directly obtain correspondences as classifier scores. We also introduce a formulation of visual context that is flexible, efficient to compute, and can capture relationships in the entire image plane. The original binary descriptors are augmented with contextual information and informative features are selected by the boosting framework. Through detailed experiments, we evaluate the retrieval quality and performance of LandmarkBoost, demonstrating that it outperforms common state-of-the-art descriptor matching methods.

##### Abstract (translated by Google)
自治系统的日益普及产生了对可靠和有效的度量姿势检索算法的需求。当前使用的方法倾向于依赖二进制描述符的最近邻搜索来执行2D-3D匹配并保证移动平台上的实时能力。然而，这些方法随着地图的大小增加，视点或外观的变化以及环境中存在的视觉混叠而变得困难。严格定义的描述符模式仅捕获关键点的有限邻域并完全忽略整体视觉上下文。
 我们提出LandmarkBoost--与传统的2D-3D匹配方法相比，这种方法将搜索问题作为一个具有里程碑意义的分类任务。我们使用增强分类器对地标观测进行分类，并直接获得作为分类器分数的对应关系。我们还介绍了一种灵活，高效计算的视觉上下文，并可以捕捉整个图像平面中的关系。原始二进制描述符用上下文信息增强，并且增强框架选择信息特征。通过详细的实验，我们评估了LandmarkBoost的检索质量和性能，证明它优于常见的最先进的描述符匹配方法。

##### URL
[http://arxiv.org/abs/1807.04702](http://arxiv.org/abs/1807.04702)

##### PDF
[http://arxiv.org/pdf/1807.04702](http://arxiv.org/pdf/1807.04702)

