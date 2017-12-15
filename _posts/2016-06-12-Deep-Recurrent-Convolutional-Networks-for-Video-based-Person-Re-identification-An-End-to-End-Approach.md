---
layout: post
title: "Deep Recurrent Convolutional Networks for Video-based Person Re-identification: An End-to-End Approach"
date: 2016-06-12 10:52:09
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN
author: Lin Wu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an end-to-end approach to simultaneously learn spatio-temporal features and corresponding similarity metric for video-based person re-identification. Given the video sequence of a person, features from each frame that are extracted from all levels of a deep convolutional network can preserve a higher spatial resolution from which we can model finer motion patterns. These low-level visual percepts are leveraged into a variant of recurrent model to characterize the temporal variation between time-steps. Features from all time-steps are then summarized using temporal pooling to produce an overall feature representation for the complete sequence. The deep convolutional network, recurrent layer, and the temporal pooling are jointly trained to extract comparable hidden-unit representations from input pair of time series to compute their corresponding similarity value. The proposed framework combines time series modeling and metric learning to jointly learn relevant features and a good similarity measure between time sequences of person. Experiments demonstrate that our approach achieves the state-of-the-art performance for video-based person re-identification on iLIDS-VID and PRID 2011, the two primary public datasets for this purpose.

##### Abstract (translated by Google)
在本文中，我们提出了一种端到端的方法来同时学习时空特征和基于视频的人重新识别的相应的相似性度量。给定人的视频序列，从深度卷积网络的各个层次提取的每个帧的特征可以保持较高的空间分辨率，从而我们可以对更精细的运动模式进行建模。这些低级别的视觉感受被用于反复模型的变体来表征时间步长之间的时间变化。然后总结所有时间步骤的特征，使用时间汇集来产生完整序列的总体特征表示。对深度卷积网络，递归层和时间池进行联合训练，从输入的时间序列对中提取可比较的隐含单位表示，计算出相应的相似度值。所提出的框架将时间序列建模和度量学习相结合，共同学习人的时间序列之间的相关特征和良好的相似性度量。实验证明，我们的方法实现了在iLIDS-VID和PRID 2011（为此目的的两个主要公共数据集）上基于视频的人员重新识别的最新性能。

##### URL
[https://arxiv.org/abs/1606.01609](https://arxiv.org/abs/1606.01609)

##### PDF
[https://arxiv.org/pdf/1606.01609](https://arxiv.org/pdf/1606.01609)

