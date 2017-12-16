---
layout: post
title: "Block-Matching Optical Flow for Dynamic Vision Sensor- Algorithm and FPGA Implementation"
date: 2017-06-16 19:45:47
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Min Liu, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
Rapid and low power computation of optical flow (OF) is potentially useful in robotics. The dynamic vision sensor (DVS) event camera produces quick and sparse output, and has high dynamic range, but conventional OF algorithms are frame-based and cannot be directly used with event-based cameras. Previous DVS OF methods do not work well with dense textured input and are designed for implementation in logic circuits. This paper proposes a new block-matching based DVS OF algorithm which is inspired by motion estimation methods used for MPEG video compression. The algorithm was implemented both in software and on FPGA. For each event, it computes the motion direction as one of 9 directions. The speed of the motion is set by the sample interval. Results show that the Average Angular Error can be improved by 30\% compared with previous methods. The OF can be calculated on FPGA with 50\,MHz clock in 0.2\,us per event (11 clock cycles), 20 times faster than a Java software implementation running on a desktop PC. Sample data is shown that the method works on scenes dominated by edges, sparse features, and dense texture.

##### Abstract (translated by Google)
光流（OF）的快速和低功率计算在机器人技术中可能是有用的。动态视觉传感器（DVS）事件摄像机产生快速和稀疏的输出，并具有高动态范围，但传统的OF算法是基于帧的，不能直接用于基于事件的摄像机。先前的DVS OF方法不适用于密集的纹理输入，并且是为在逻辑电路中实现而设计的。本文提出了一种基于块匹配的DVS OF算法，该算法受MPEG视频压缩运动估计方法的启发。该算法是在软件和FPGA上实现的。对于每个事件，它将运动方向计算为9个方向之一。运动速度由采样间隔设置。结果表明，与以前的方法相比，平均角误差可以提高30％。 OF可以在FPGA上以每个事件（11个时钟周期）的0.2 \ us，50 \，MHz时钟来计算，比在台式PC上运行的Java软件实现快20倍。示例数据显示该方法适用于由边缘，稀疏特征和密集纹理支配的场景。

##### URL
[https://arxiv.org/abs/1706.05415](https://arxiv.org/abs/1706.05415)

##### PDF
[https://arxiv.org/pdf/1706.05415](https://arxiv.org/pdf/1706.05415)

