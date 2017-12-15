---
layout: post
title: "Fast Object Localization Using a CNN Feature Map Based Multi-Scale Search"
date: 2016-04-12 18:44:10
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Hyungtae Lee, Heesung Kwon, Archith J. Bency, William D. Nothwang
mathjax: true
---

* content
{:toc}

##### Abstract
Object localization is an important task in computer vision but requires a large amount of computational power due mainly to an exhaustive multiscale search on the input image. In this paper, we describe a near real-time multiscale search on a deep CNN feature map that does not use region proposals. The proposed approach effectively exploits local semantic information preserved in the feature map of the outermost convolutional layer. A multi-scale search is performed on the feature map by processing all the sub-regions of different sizes using separate expert units of fully connected layers. Each expert unit receives as input local semantic features only from the corresponding sub-regions of a specific geometric shape. Therefore, it contains more nearly optimal parameters tailored to the corresponding shape. This multi-scale and multi-aspect ratio scanning strategy can effectively localize a potential object of an arbitrary size. The proposed approach is fast and able to localize objects of interest with a frame rate of 4 fps while providing improved detection performance over the state-of-the art on the PASCAL VOC 12 and MSCOCO data sets.

##### Abstract (translated by Google)
目标定位是计算机视觉中的一项重要任务，但主要是由于对输入图像进行穷举式多尺度搜索，因此需要大量的计算能力。在本文中，我们描述了一个不使用区域提议的深度CNN特征映射上的近实时多尺度搜索。该方法有效地利用了最外层卷积层特征映射中保存的局部语义信息。通过使用独立的完全连接层的专家单元处理不同大小的所有子区域，在特征地图上执行多尺度搜索。每个专家单元仅从特定几何形状的对应子区域接收作为输入的本地语义特征。因此，它包含更适合相应形状的最佳参数。这种多尺度，多纵横比的扫描策略可以有效地定位任意大小的潜在对象。所提出的方法是快速的并且能够以4fps的帧速率定位感兴趣的对象，同时提供比PASCAL VOC 12和MSCOCO数据集中的现有技术更好的检测性能。

##### URL
[https://arxiv.org/abs/1604.03517](https://arxiv.org/abs/1604.03517)

##### PDF
[https://arxiv.org/pdf/1604.03517](https://arxiv.org/pdf/1604.03517)

