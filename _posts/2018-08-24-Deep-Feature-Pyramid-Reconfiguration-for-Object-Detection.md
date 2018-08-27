---
layout: post
title: "Deep Feature Pyramid Reconfiguration for Object Detection"
date: 2018-08-24 03:17:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Tao Kong, Fuchun Sun, Wenbing Huang, Huaping Liu
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art object detectors usually learn multi-scale representations to get better results by employing feature pyramids. However, the current designs for feature pyramids are still inefficient to integrate the semantic information over different scales. In this paper, we begin by investigating current feature pyramids solutions, and then reformulate the feature pyramid construction as the feature reconfiguration process. Finally, we propose a novel reconfiguration architecture to combine low-level representations with high-level semantic features in a highly-nonlinear yet efficient way. In particular, our architecture which consists of global attention and local reconfigurations, is able to gather task-oriented features across different spatial locations and scales, globally and locally. Both the global attention and local reconfiguration are lightweight, in-place, and end-to-end trainable. Using this method in the basic SSD system, our models achieve consistent and significant boosts compared with the original model and its other variations, without losing real-time processing speed.

##### Abstract (translated by Google)
最先进的物体探测器通常通过使用特征金字塔来学习多尺度表示以获得更好的结果。然而，特征金字塔的当前设计仍然无法在不同尺度上集成语义信息。在本文中，我们首先研究当前特征金字塔解决方案，然后重新构造特征金字塔结构作为特征重构过程。最后，我们提出了一种新颖的重新配置架构，以高度非线性且高效的方式将低级表示与高级语义特征相结合。特别是，我们的架构由全球关注和本地重新配置组成，能够在全球和本地的不同空间位置和规模上收集面向任务的功能。全球关注和本地重新配置都是轻量级的，就地的，端到端的可训练的。在基本SSD系统中使用此方法，与原始模型及其他变体相比，我们的模型可实现一致且显着的提升，而不会失去实时处理速度。

##### URL
[http://arxiv.org/abs/1808.07993](http://arxiv.org/abs/1808.07993)

##### PDF
[http://arxiv.org/pdf/1808.07993](http://arxiv.org/pdf/1808.07993)

