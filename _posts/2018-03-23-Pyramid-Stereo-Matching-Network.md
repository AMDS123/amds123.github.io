---
layout: post
title: "Pyramid Stereo Matching Network"
date: 2018-03-23 06:40:09
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jia-Ren Chang, Yong-Sheng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that depth estimation from a stereo pair of images can be formulated as a supervised learning task to be resolved with convolutional neural networks (CNNs). However, current architectures rely on patch-based Siamese networks, lacking the means to exploit context information for finding correspondence in illposed regions. To tackle this problem, we propose PSMNet, a pyramid stereo matching network consisting of two main modules: spatial pyramid pooling and 3D CNN. The spatial pyramid pooling module takes advantage of the capacity of global context information by aggregating context in different scales and locations to form a cost volume. The 3D CNN learns to regularize cost volume using stacked multiple hourglass networks in conjunction with intermediate supervision. The proposed approach was evaluated on several benchmark datasets. Our method ranked first in the KITTI 2012 and 2015 leaderboards before March 18, 2018. The codes of PSMNet are available at: this https URL

##### Abstract (translated by Google)
最近的研究表明，从一对立体图像进行深度估计可以被制定为一个监督学习任务，用卷积神经网络（CNN）来解决。然而，目前的体系结构依赖于基于补丁的连体网络，缺乏利用上下文信息来查找在所示区域的对应关系的手段。为了解决这个问题，我们提出PSMNet，一个由两个主要模块组成的金字塔立体匹配网络：空间金字塔池和3D CNN。空间金字塔池模块通过聚合不同尺度和位置的上下文来利用全局上下文信息的能力来形成成本体积。 3D CNN学习使用堆叠的多个沙漏网络结合中间监督来调整成本体积。所提出的方法在几个基准数据集上进行了评估。我们的方法在2018年3月18日之前的KITTI 2012和2015排行榜中排名第一。PSMNet的代码位于：https https

##### URL
[https://arxiv.org/abs/1803.08669](https://arxiv.org/abs/1803.08669)

##### PDF
[https://arxiv.org/pdf/1803.08669](https://arxiv.org/pdf/1803.08669)

