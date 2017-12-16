---
layout: post
title: "Combining LiDAR Space Clustering and Convolutional Neural Networks for Pedestrian Detection"
date: 2017-10-17 08:40:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Damien Matti, Hazım Kemal Ekenel, Jean-Philippe Thiran
mathjax: true
---

* content
{:toc}

##### Abstract
Pedestrian detection is an important component for safety of autonomous vehicles, as well as for traffic and street surveillance. There are extensive benchmarks on this topic and it has been shown to be a challenging problem when applied on real use-case scenarios. In purely image-based pedestrian detection approaches, the state-of-the-art results have been achieved with convolutional neural networks (CNN) and surprisingly few detection frameworks have been built upon multi-cue approaches. In this work, we develop a new pedestrian detector for autonomous vehicles that exploits LiDAR data, in addition to visual information. In the proposed approach, LiDAR data is utilized to generate region proposals by processing the three dimensional point cloud that it provides. These candidate regions are then further processed by a state-of-the-art CNN classifier that we have fine-tuned for pedestrian detection. We have extensively evaluated the proposed detection process on the KITTI dataset. The experimental results show that the proposed LiDAR space clustering approach provides a very efficient way of generating region proposals leading to higher recall rates and fewer misses for pedestrian detection. This indicates that LiDAR data can provide auxiliary information for CNN-based approaches.

##### Abstract (translated by Google)
行人检测是自动驾驶车辆安全的重要组成部分，也是交通和街道监控的重要组成部分。在这个主题上有广泛的基准，并且在实际使用情况下被证明是一个具有挑战性的问题。在纯粹的基于图像的行人检测方法中，用卷积神经网络（CNN）已经实现了最新的结果，并且在多线索方法的基础上构建了惊人的检测框架。在这项工作中，我们开发了一种新的自主车辆行人探测器，利用LiDAR数据，除了视觉信息。在所提出的方法中，利用LiDAR数据通过处理其提供的三维点云来生成区域提议。这些候选区域然后由最先进的CNN分类器进一步处理，我们已经对行人检测进行了微调。我们已经对KITTI数据集提出的检测流程进行了广泛的评估。实验结果表明，提出的LiDAR空间聚类方法提供了一个非常有效的方法来产生区域建议，导致更高的召回率和更少的行人检测漏洞。这表明LiDAR数据可以为基于CNN的方法提供辅助信息。

##### URL
[https://arxiv.org/abs/1710.06160](https://arxiv.org/abs/1710.06160)

##### PDF
[https://arxiv.org/pdf/1710.06160](https://arxiv.org/pdf/1710.06160)

