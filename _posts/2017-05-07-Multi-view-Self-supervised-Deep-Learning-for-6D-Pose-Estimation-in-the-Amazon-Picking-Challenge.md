---
layout: post
title: "Multi-view Self-supervised Deep Learning for 6D Pose Estimation in the Amazon Picking Challenge"
date: 2017-05-07 20:12:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation CNN Deep_Learning
author: Andy Zeng, Kuan-Ting Yu, Shuran Song, Daniel Suo, Ed Walker Jr., Alberto Rodriguez, Jianxiong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
Robot warehouse automation has attracted significant interest in recent years, perhaps most visibly in the Amazon Picking Challenge (APC). A fully autonomous warehouse pick-and-place system requires robust vision that reliably recognizes and locates objects amid cluttered environments, self-occlusions, sensor noise, and a large variety of objects. In this paper we present an approach that leverages multi-view RGB-D data and self-supervised, data-driven learning to overcome those difficulties. The approach was part of the MIT-Princeton Team system that took 3rd- and 4th- place in the stowing and picking tasks, respectively at APC 2016. In the proposed approach, we segment and label multiple views of a scene with a fully convolutional neural network, and then fit pre-scanned 3D object models to the resulting segmentation to get the 6D object pose. Training a deep neural network for segmentation typically requires a large amount of training data. We propose a self-supervised method to generate a large labeled dataset without tedious manual segmentation. We demonstrate that our system can reliably estimate the 6D pose of objects under a variety of scenarios. All code, data, and benchmarks are available at this http URL

##### Abstract (translated by Google)
机器人仓库自动化近年来引起了极大的兴趣，也许最明显的是在亚马逊采摘挑战（APC）中。一个完全自主的仓库拾放系统需要强大的视觉能力，在杂乱的环境，自我遮挡，传感器噪声和各种各样的物体中可靠识别和定位物体。在本文中，我们提出了一种利用多视图RGB-D数据和自我监督的数据驱动学习来克服这些困难的方法。该方法是麻省理工学院 - 普林斯顿大学团队系统的一部分，在APC 2016分别在第3和第4位放置和选取任务。在提出的方法中，我们使用完全卷积神经分割和标记场景的多个视图网络，然后将预先扫描的三维物体模型拟合到所得到的分割中以获得6D物体姿态。训练深度神经网络进行分割通常需要大量的训练数据。我们提出了一个自我监督的方法来生成一个大的标记数据集，而无需繁琐的手动分割。我们证明，我们的系统可以可靠地估计各种场景下物体的6D姿态。所有的代码，数据和基准都可以在这个http URL中找到

##### URL
[https://arxiv.org/abs/1609.09475](https://arxiv.org/abs/1609.09475)

##### PDF
[https://arxiv.org/pdf/1609.09475](https://arxiv.org/pdf/1609.09475)

