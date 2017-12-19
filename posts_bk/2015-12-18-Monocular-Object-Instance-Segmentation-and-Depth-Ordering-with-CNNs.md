---
layout: post
title: "Monocular Object Instance Segmentation and Depth Ordering with CNNs"
date: 2015-12-18 00:38:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Ziyu Zhang, Alexander G. Schwing, Sanja Fidler, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we tackle the problem of instance-level segmentation and depth ordering from a single monocular image. Towards this goal, we take advantage of convolutional neural nets and train them to directly predict instance-level segmentations where the instance ID encodes the depth ordering within image patches. To provide a coherent single explanation of an image we develop a Markov random field which takes as input the predictions of convolutional neural nets applied at overlapping patches of different resolutions, as well as the output of a connected component algorithm. It aims to predict accurate instance-level segmentation and depth ordering. We demonstrate the effectiveness of our approach on the challenging KITTI benchmark and show good performance on both tasks.

##### Abstract (translated by Google)
在本文中，我们从单个单目图像解决实例级分割和深度排序的问题。为了实现这个目标，我们利用卷积神经网络并训练它们直接预测实例ID对实例ID编码图像块内的深度排序的实例级分割。为了提供一个图像的连贯的单一解释，我们开发了一个马尔可夫随机场，其中输入了在不同分辨率的重叠片上应用的卷积神经网络的预测以及连接分量算法的输出。它旨在预测准确的实例级分割和深度排序。我们在具有挑战性的KITTI基准测试中证明了我们的方法的有效性，并在两项任务中表现出良好的性能

##### URL
[https://arxiv.org/abs/1505.03159](https://arxiv.org/abs/1505.03159)

##### PDF
[https://arxiv.org/pdf/1505.03159](https://arxiv.org/pdf/1505.03159)

