---
layout: post
title: "Pose-conditioned Spatio-Temporal Attention for Human Action Recognition"
date: 2017-08-07 02:04:08
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition CNN RNN Recognition
author: Fabien Baradel, Christian Wolf, Julien Mille
mathjax: true
---

* content
{:toc}

##### Abstract
We address human action recognition from multi-modal video data involving articulated pose and RGB frames and propose a two-stream approach. The pose stream is processed with a convolutional model taking as input a 3D tensor holding data from a sub-sequence. A specific joint ordering, which respects the topology of the human body, ensures that different convolutional layers correspond to meaningful levels of abstraction. The raw RGB stream is handled by a spatio-temporal soft-attention mechanism conditioned on features from the pose network. An LSTM network receives input from a set of image locations at each instant. A trainable glimpse sensor extracts features on a set of predefined locations specified by the pose stream, namely the 4 hands of the two people involved in the activity. Appearance features give important cues on hand motion and on objects held in each hand. We show that it is of high interest to shift the attention to different hands at different time steps depending on the activity itself. Finally a temporal attention mechanism learns how to fuse LSTM features over time. We evaluate the method on 3 datasets. State-of-the-art results are achieved on the largest dataset for human activity recognition, namely NTU-RGB+D, as well as on the SBU Kinect Interaction dataset. Performance close to state-of-the-art is achieved on the smaller MSR Daily Activity 3D dataset.

##### Abstract (translated by Google)
我们从涉及铰接姿势和RGB帧的多模式视频数据处理人类动作识别，并提出了一种双流方法。姿态流用卷积模型进行处理，其中输入3D张量保持来自子序列的数据。尊重人体拓扑结构的特定联合排序确保了不同的卷积层对应于有意义的抽象层次。原始的RGB流由一个时空软注意机制来处理，该机制以来自姿态网络的特征为条件。 LSTM网络在每个时刻接收来自一组图像位置的输入。可训练的一瞥传感器提取由姿势流指定的一组预定位置上的特征，即参与活动的两个人的四只手。外观特征为手部运动提供了重要的线索，并为每只手握住了物体。我们表明，根据活动本身，在不同的时间步骤将注意力转移到不同的手上，这是高度兴趣的。最后一个时间关注机制学习如何融合LSTM功能随着时间的推移。我们评估3个数据集的方法。在最大的人类活动识别数据集NTU-RGB + D以及SBU Kinect Interaction数据集上实现了最先进的结果。在较小的MSR日常活动3D数据集上实现接近最先进水平的性能。

##### URL
[https://arxiv.org/abs/1703.10106](https://arxiv.org/abs/1703.10106)

##### PDF
[https://arxiv.org/pdf/1703.10106](https://arxiv.org/pdf/1703.10106)

