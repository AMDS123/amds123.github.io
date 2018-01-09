---
layout: post
title: "Ensemble One-dimensional Convolution Neural Networks for Skeleton-based Action Recognition"
date: 2018-01-08 15:12:54
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition CNN Recognition
author: Yangyang Xu, Lei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we proposed a effective but extensible residual one-dimensional convolution neural network as base network, based on the this network, we proposed four subnets to explore the features of skeleton sequences from each aspect. Given a skeleton sequences, the spatial information are encoded into the skeleton joints coordinate in a frame and the temporal information are present by multiple frames. Limited by the skeleton sequence representations, two-dimensional convolution neural network cannot be used directly, we chose one-dimensional convolution layer as the basic layer. Each sub network could extract discriminative features from different aspects. Our first subnet is a two-stream network which could explore both temporal and spatial information. The second is a body-parted network, which could gain micro spatial features and macro temporal features. The third one is an attention network, the main contribution of which is to focus the key frames and feature channels which high related with the action classes in a skeleton sequence. One frame-difference network, as the last subnet, mainly processes the joints changes between the consecutive frames. Four subnets ensemble together by late fusion, the key problem of ensemble method is each subnet should have a certain performance and between the subnets, there are diversity existing. Each subnet shares a wellperformance basenet and differences between subnets guaranteed the diversity. Experimental results show that the ensemble network gets a state-of-the-art performance on three widely used datasets.

##### Abstract (translated by Google)
本文提出了一种有效但可扩展的残差一维卷积神经网络作为基础网络，在此网络的基础上提出了四个子网，从各个方面探讨了骨架序列的特征。给定一个骨架序列，空间信息被编码成框架中的骨架关节坐标，并且时间信息由多个框架存在。受限于骨架序列表示，二维卷积神经网络不能直接使用，我们选择一维卷积层作为基本层。每个子网络可以从不同方面提取区分特征。我们的第一个子网是一个可以探索时间和空间信息的双流网络。其次是一个分体网络，可以获得微观空间特征和宏观时空特征。第三个是关注网络，其主要贡献是将与动作类别高度相关的关键帧和特征通道集中在骨架序列中。一个帧差分网络作为最后一个子网，主要处理连续帧之间的关节变化。四子网融合后期融合，集成方法的核心问题是每个子网应具备一定的性能和子网间存在的多样性。每个子网共享一个良好的基础网络，子网之间的差异保证了多样性。实验结果表明，集成网络在三个广泛使用的数据集上获得了最先进的性能。

##### URL
[http://arxiv.org/abs/1801.02475](http://arxiv.org/abs/1801.02475)

##### PDF
[http://arxiv.org/pdf/1801.02475](http://arxiv.org/pdf/1801.02475)

