---
layout: post
title: "Encoding Multi-Resolution Brain Networks Using Unsupervised Deep Learning"
date: 2017-08-13 01:43:11
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Arash Rahnama, Abdullah Alchihabi, Vijay Gupta, Panos Antsaklis, Fatos T. Yarman Vural
mathjax: true
---

* content
{:toc}

##### Abstract
The main goal of this study is to extract a set of brain networks in multiple time-resolutions to analyze the connectivity patterns among the anatomic regions for a given cognitive task. We suggest a deep architecture which learns the natural groupings of the connectivity patterns of human brain in multiple time-resolutions. The suggested architecture is tested on task data set of Human Connectome Project (HCP) where we extract multi-resolution networks, each of which corresponds to a cognitive task. At the first level of this architecture, we decompose the fMRI signal into multiple sub-bands using wavelet decompositions. At the second level, for each sub-band, we estimate a brain network extracted from short time windows of the fMRI signal. At the third level, we feed the adjacency matrices of each mesh network at each time-resolution into an unsupervised deep learning algorithm, namely, a Stacked De- noising Auto-Encoder (SDAE). The outputs of the SDAE provide a compact connectivity representation for each time window at each sub-band of the fMRI signal. We concatenate the learned representations of all sub-bands at each window and cluster them by a hierarchical algorithm to find the natural groupings among the windows. We observe that each cluster represents a cognitive task with a performance of 93% Rand Index and 71% Adjusted Rand Index. We visualize the mean values and the precisions of the networks at each component of the cluster mixture. The mean brain networks at cluster centers show the variations among cognitive tasks and the precision of each cluster shows the within cluster variability of networks, across the subjects.

##### Abstract (translated by Google)
这项研究的主要目标是提取一个多时间分辨率的大脑网络，以分析一个给定的认知任务解剖区域之间的连接模式。我们提出了一个深入的体系结构，它可以在多个时间分辨率下学习人脑连接模式的自然分组。建议的架构在Human Connectome Project（HCP）的任务数据集上进行测试，我们提取多分辨率网络，每个网络对应一个认知任务。在这个架构的第一层，我们使用小波分解将fMRI信号分解成多个子带。在第二级，对于每个子带，我们估计从fMRI信号的短时间窗提取的脑网络。在第三层，我们把每个网格网络在每个时间分辨率下的邻接矩阵送入一个无监督的深度学习算法，即一个堆叠降噪自动编码器（SDAE）。 SDAE的输出为fMRI信号的每个子带上的每个时间窗提供紧凑的连接表示。我们连接每个窗口的所有子带的学习表示，并通过分层算法将它们聚类，以在窗口之间找到自然分组。我们观察到，每个集群代表一个认知任务，表现为93％的兰德指数和71％的调整兰德指数。我们可以看到在群集混合的每个组件的网络的平均值和精度。聚类中心的平均脑网络显示了认知任务之间的差异，每个聚类的精度显示了网络内的聚类变异。

##### URL
[https://arxiv.org/abs/1708.04232](https://arxiv.org/abs/1708.04232)

##### PDF
[https://arxiv.org/pdf/1708.04232](https://arxiv.org/pdf/1708.04232)

