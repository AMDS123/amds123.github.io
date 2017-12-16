---
layout: post
title: "YoTube: Searching Action Proposal via Recurrent and Static Regression Networks"
date: 2017-06-26 03:52:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection RNN Prediction Detection
author: Hongyuan Zhu, Romain Vial, Shijian Lu, Yonghong Tian, Xianbin Cao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present YoTube-a novel network fusion framework for searching action proposals in untrimmed videos, where each action proposal corresponds to a spatialtemporal video tube that potentially locates one human action. Our method consists of a recurrent YoTube detector and a static YoTube detector, where the recurrent YoTube explores the regression capability of RNN for candidate bounding boxes predictions using learnt temporal dynamics and the static YoTube produces the bounding boxes using rich appearance cues in a single frame. Both networks are trained using rgb and optical flow in order to fully exploit the rich appearance, motion and temporal context, and their outputs are fused to produce accurate and robust proposal boxes. Action proposals are finally constructed by linking these boxes using dynamic programming with a novel trimming method to handle the untrimmed video effectively and efficiently. Extensive experiments on the challenging UCF-101 and UCF-Sports datasets show that our proposed technique obtains superior performance compared with the state-of-the-art.

##### Abstract (translated by Google)
在本文中，我们介绍YoTube--一种新颖的网络融合框架，用于在未修剪的视频中搜索动作提议，其中每个动作提议对应于可能定位一个人类动作的空间时间视频管。我们的方法由一个经常性的YoTube探测器和一个静态的YoTube探测器组成，其中经常性的YoTube探测RNN对于使用学习的时间动态的候选边界框预测的回归能力，并且静态YoTube使用单帧中丰富的外观线索产生边界框。两个网络都使用rgb和光流进行训练，以便充分利用丰富的外观，运动和时间环境，并将它们的输出进行融合，从而生成精确和健壮的提案框。通过使用动态编程将这些框与新的调整方法联系起来以有效和高效地处理未修剪的视频，动作提议最终被构建。在具有挑战性的UCF-101和UCF-体育数据集上进行的大量实验表明，我们提出的技术与现有技术相比获得了优越的性能。

##### URL
[https://arxiv.org/abs/1706.08218](https://arxiv.org/abs/1706.08218)

##### PDF
[https://arxiv.org/pdf/1706.08218](https://arxiv.org/pdf/1706.08218)

