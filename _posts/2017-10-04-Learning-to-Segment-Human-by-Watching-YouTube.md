---
layout: post
title: "Learning to Segment Human by Watching YouTube"
date: 2017-10-04 04:16:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised CNN Semantic_Segmentation Optimization Inference Detection
author: Xiaodan Liang, Yunchao Wei, Liang Lin, Yunpeng Chen, Xiaohui Shen, Jianchao Yang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
An intuition on human segmentation is that when a human is moving in a video, the video-context (e.g., appearance and motion clues) may potentially infer reasonable mask information for the whole human body. Inspired by this, based on popular deep convolutional neural networks (CNN), we explore a very-weakly supervised learning framework for human segmentation task, where only an imperfect human detector is available along with massive weakly-labeled YouTube videos. In our solution, {the video-context guided human mask inference and CNN based segmentation network learning iterate to mutually enhance each other until no further improvement gains.} In the first step, each video is decomposed into supervoxels by the unsupervised video segmentation. The superpixels within the supervoxels are then classified as human or non-human by graph optimization with unary energies from the imperfect human detection results and the predicted confidence maps by the CNN trained in the previous iteration. In the second step, the video-context derived human masks are used as direct labels to train CNN. Extensive experiments on the challenging PASCAL VOC 2012 semantic segmentation benchmark demonstrate that the proposed framework has already achieved superior results than all previous weakly-supervised methods with object class or bounding box annotations. In addition, by augmenting with the annotated masks from PASCAL VOC 2012, our method reaches a new state-of-the-art performance on the human segmentation task.

##### Abstract (translated by Google)
关于人体分割的直觉是，当人在视频中移动时，视频背景（例如外观和运动线索）可能潜在地推断整个人体的合理掩模信息。受此启发，基于流行的深度卷积神经网络（CNN），我们探索了一个用于人体分割任务的非常弱监督的学习框架，其中只有一个不完善的人体检测器以及大量弱标记的YouTube视频。在我们的解决方案中，视频上下文引导的人脸面部推断和基于CNN的分割网络学习迭代相互增强，直到没有进一步的改进增益。第一步，通过无监督的视频分割将每个视频分解成超体素。超像素内的超像素随后通过图形优化被分类为人类或非人类，其中一元能量来自不完美的人类检测结果，并且由先前迭代中训练的CNN预测置信度图。在第二步中，将视频上下文派生的人脸蒙版用作直接标签来训练CNN。在具有挑战性的PASCAL VOC 2012语义分割基准测试中进行的大量实验证明，所提出的框架已经比以前的所有具有对象类或边界框注释的弱监督方法获得了更好的结果。此外，通过增加PASCAL VOC 2012的注释面罩，我们的方法在人体分割任务上达到了最新的最新性能。

##### URL
[https://arxiv.org/abs/1710.01457](https://arxiv.org/abs/1710.01457)

##### PDF
[https://arxiv.org/pdf/1710.01457](https://arxiv.org/pdf/1710.01457)

