---
layout: post
title: "Human Activity Recognition in RGB-D Videos by Dynamic Images"
date: 2018-07-09 05:28:19
categories: arXiv_CV
tags: arXiv_CV Sparse Recognition
author: Snehasis Mukherjee, Leburu Anvitha, T. Mohana Lahari
mathjax: true
---

* content
{:toc}

##### Abstract
Human Activity Recognition in RGB-D videos has been an active research topic during the last decade. However, no efforts have been found in the literature, for recognizing human activity in RGB-D videos where several performers are performing simultaneously. In this paper we introduce such a challenging dataset with several performers performing the activities. We present a novel method for recognizing human activities in such videos. The proposed method aims in capturing the motion information of the whole video by producing a dynamic image corresponding to the input video. We use two parallel ResNext-101 to produce the dynamic images for the RGB video and depth video separately. The dynamic images contain only the motion information and hence, the unnecessary background information are eliminated. We send the two dynamic images extracted from the RGB and Depth videos respectively, through a fully connected layer of neural networks. The proposed dynamic image reduces the complexity of the recognition process by extracting a sparse matrix from a video. However, the proposed system maintains the required motion information for recognizing the activity. The proposed method has been tested on the MSR Action 3D dataset and has shown comparable performances with respect to the state-of-the-art. We also apply the proposed method on our own dataset, where the proposed method outperforms the state-of-the-art approaches.

##### Abstract (translated by Google)
在过去十年中，RGB-D视频中的人类活动识别一直是一个活跃的研究课题。然而，在文献中没有找到用于识别RGB-D视频中的人类活动的努力，其中几个表演者同时进行。在本文中，我们介绍了这样一个具有挑战性的数据集，其中有几个执行者正在执我们提出了一种识别此类视频中人类活动的新方法。所提出的方法旨在通过产生与输入视频相对应的动态图像来捕获整个视频的运动信息。我们使用两个并行的ResNext-101分别为RGB视频和深度视频生成动态图像。动态图像仅包含运动信息，因此消除了不必要的背景信息。我们分别通过完全连接的神经网络层发送从RGB和深度视频中提取的两个动态图像。所提出的动态图像通过从视频中提取稀疏矩阵来降低识别过程的复杂性。然而，所提出的系统维持用于识别活动的所需运动信息。所提出的方法已经在MSR Action 3D数据集上进行了测试，并且已经显示出与现有技术相当的性能。我们还在我们自己的数据集上应用所提出的方法，其中所提出的方法优于最先进的方法。

##### URL
[http://arxiv.org/abs/1807.02947](http://arxiv.org/abs/1807.02947)

##### PDF
[http://arxiv.org/pdf/1807.02947](http://arxiv.org/pdf/1807.02947)

