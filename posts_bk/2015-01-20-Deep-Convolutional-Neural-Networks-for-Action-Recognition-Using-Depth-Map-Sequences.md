---
layout: post
title: "Deep Convolutional Neural Networks for Action Recognition Using Depth Map Sequences"
date: 2015-01-20 00:46:10
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Deep_Learning Recognition
author: Pichao Wang, Wanqing Li, Zhimin Gao, Jing Zhang, Chang Tang, Philip Ogunbona
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep learning approach has achieved promising results in various fields of computer vision. In this paper, a new framework called Hierarchical Depth Motion Maps (HDMM) + 3 Channel Deep Convolutional Neural Networks (3ConvNets) is proposed for human action recognition using depth map sequences. Firstly, we rotate the original depth data in 3D pointclouds to mimic the rotation of cameras, so that our algorithms can handle view variant cases. Secondly, in order to effectively extract the body shape and motion information, we generate weighted depth motion maps (DMM) at several temporal scales, referred to as Hierarchical Depth Motion Maps (HDMM). Then, three channels of ConvNets are trained on the HDMMs from three projected orthogonal planes separately. The proposed algorithms are evaluated on MSRAction3D, MSRAction3DExt, UTKinect-Action and MSRDailyActivity3D datasets respectively. We also combine the last three datasets into a larger one (called Combined Dataset) and test the proposed method on it. The results show that our approach can achieve state-of-the-art results on the individual datasets and without dramatical performance degradation on the Combined Dataset.

##### Abstract (translated by Google)
近年来，深度学习方法在计算机视觉的各个领域取得了可喜的成果。本文提出了一种新的基于深度图序列的层次深度运动图（HDMM）+三通道深度卷积神经网络（3ConvNets）。首先，我们旋转三维点云的原始深度数据，以模仿相机的旋转，以便我们的算法可以处理视图变体的情况。其次，为了有效地提取人体形状和运动信息，我们在多个时间尺度上生成加权深度运动图（DMM），称为分层深度运动图（HDMM）。然后，从三个投影正交平面分别在HDMM上训练三个通道的通道。所提出的算法分别在MSRAction3D，MSRAction3DExt，UTKinect-Action和MSRDailyActivity3D数据集上评估。我们还将最后三个数据集组合成一个更大的数据集（称为组合数据集）并对其进行测试。结果表明，我们的方法可以在单个数据集上实现最新的结果，并且在组合数据集上没有显着的性能下降。

##### URL
[https://arxiv.org/abs/1501.04686](https://arxiv.org/abs/1501.04686)

##### PDF
[https://arxiv.org/pdf/1501.04686](https://arxiv.org/pdf/1501.04686)

