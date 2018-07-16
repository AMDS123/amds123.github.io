---
layout: post
title: "Video-based Person Re-identification via 3D Convolutional Networks and Non-local Attention"
date: 2018-07-12 05:30:26
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification Action_Recognition CNN RNN Recognition
author: Xingyu Liao, Lingxiao He, Zhouwang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Video-based person re-identification (ReID) is a challenging problem, where some video tracks of people across non-overlapping cameras are available for matching. Feature aggregation from a video track is a key step for video-based person ReID. Many existing methods tackle this problem by average/maximum temporal pooling or RNNs with attention. However, these methods cannot deal with temporal dependency and spatial misalignment problems at the same time. We are inspired by video action recognition that involves the identification of different actions from video tracks. Firstly, we use 3D convolutions on video volume, instead of using 2D convolutions across frames, to extract spatial and temporal features simultaneously. Secondly, we use a non-local block to tackle the misalignment problem and capture spatial-temporal long-range dependencies. As a result, the network can learn useful spatial-temporal information as a weighted sum of the features in all space and temporal positions in the input feature map. Experimental results on three datasets show that our framework outperforms state-of-the-art approaches by a large margin on multiple metrics.

##### Abstract (translated by Google)
基于视频的人员重新识别（ReID）是一个具有挑战性的问题，其中跨越非重叠相机的人的一些视频轨道可用于匹配。来自视频轨道的特征聚合是基于视频的人ReID的关键步骤。许多现有方法通过平均/最大时间池或具有注意力的RNN来解决该问题。然而，这些方法不能同时处理时间依赖性和空间错位问题。我们受到视频动作识别的启发，涉及识别视频轨道中的不同动作。首先，我们在视频音量上使用3D卷积，而不是跨帧使用2D卷积，以同时提取空间和时间特征。其次，我们使用非局部块来解决错位问题并捕获时空的长程依赖性。结果，网络可以将有用的时空信息学习为输入特征图中的所有空间和时间位置中的特征的加权和。三个数据集的实验结果表明，我们的框架在多个指标上的表现优于最先进的方法。

##### URL
[http://arxiv.org/abs/1807.05073](http://arxiv.org/abs/1807.05073)

##### PDF
[http://arxiv.org/pdf/1807.05073](http://arxiv.org/pdf/1807.05073)

