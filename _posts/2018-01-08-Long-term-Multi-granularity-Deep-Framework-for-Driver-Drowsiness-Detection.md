---
layout: post
title: "Long-term Multi-granularity Deep Framework for Driver Drowsiness Detection"
date: 2018-01-08 07:21:46
categories: arXiv_CV
tags: arXiv_CV Face CNN Detection Relation
author: Jie Lyu, Zejian Yuan, Dapeng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
For real-world driver drowsiness detection from videos, the variation of head pose is so large that the existing methods on global face is not capable of extracting effective features, such as looking aside and lowering head. Temporal dependencies with variable length are also rarely considered by the previous approaches, e.g., yawning and speaking. In this paper, we propose a Long-term Multi-granularity Deep Framework to detect driver drowsiness in driving videos containing the frontal faces. The framework includes two key components: (1) Multi-granularity Convolutional Neural Network (MCNN), a novel network utilizes a group of parallel CNN extractors on well-aligned facial patches of different granularities, and extracts facial representations effectively for large variation of head pose, furthermore, it can flexibly fuse both detailed appearance clues of the main parts and local to global spatial constraints; (2) a deep Long Short Term Memory network is applied on facial representations to explore long-term relationships with variable length over sequential frames, which is capable to distinguish the states with temporal dependencies, such as blinking and closing eyes. Our approach achieves 90.05% accuracy and about 37 fps speed on the evaluation set of the public NTHU-DDD dataset, which is the state-of-the-art method on driver drowsiness detection. Moreover, we build a new dataset named FI-DDD, which is of higher precision of drowsy locations in temporal dimension.

##### Abstract (translated by Google)
对于视频驾驶困倦现象的人来说，头部姿态的变化是如此之大，以至于现有的全局面上的方法都不能够提取有效的特征，比如俯视和降低头部。先前的方法也很少考虑具有可变长度的时间依赖性，例如打哈欠和说话。在本文中，我们提出了一个长期的多粒度深度框架来检测驱动视频中包含正面的驾驶员困倦。该框架包括两个关键部分：（1）多粒度卷积神经网络（MCNN），在不同粒度的精确对齐的面片上利用一组并行的CNN提取器，有效提取面部表情，另外，它可以灵活地融合主要部分和局部的详细外观线索与全球空间约束; （2）在面部表征中应用深度长的短期记忆网络，探索连续帧长度变长的关系，能够区分具有时间依赖性的状态，如眨眼和闭眼。我们的方法在公共NTHU-DDD数据集的评估集上达到90.05％的准确度和大约37fps的速度，这是最先进的驾驶员困倦检测方法。此外，我们构建了一个名为FI-DDD的新数据集，该数据集在时间维度上具有较高的困倦位置精度。

##### URL
[http://arxiv.org/abs/1801.02325](http://arxiv.org/abs/1801.02325)

##### PDF
[http://arxiv.org/pdf/1801.02325](http://arxiv.org/pdf/1801.02325)

