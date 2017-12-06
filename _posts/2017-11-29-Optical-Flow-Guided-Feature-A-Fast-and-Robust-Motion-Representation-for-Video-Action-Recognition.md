---
layout: post
title: 'Optical Flow Guided Feature: A Fast and Robust Motion Representation for Video Action Recognition'
date: 2017-11-29 23:29:02
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Shuyang Sun, Zhanghui Kuang, Wanli Ouyang, Lu Sheng, Wei Zhang
---

* content
{:toc}

##### Abstract
Motion representation plays a vital role in human action recognition in videos. In this study, we introduce a novel compact motion representation for video action recognition, named Optical Flow guided Feature (OFF), which enables the network to distill temporal information through a fast and robust approach. The OFF is derived from the definition of optical flow and is orthogonal to the optical flow. By directly calculating pixel-wise spatio-temporal gradients of the deep feature maps, the OFF could be embedded in any existing CNN based video action recognition framework with only a slight additional cost. It enables the CNN to extract spatio-temporal information, especially the temporal information between frames simultaneously. This simple but powerful idea is validated by experimental results. The network with OFF fed only by RGB inputs achieves a competitive accuracy of 93.3% on UCF-101, which is comparable with the result obtained by two streams (RGB and optical flow), but is 15 times faster in speed. Experimental results also show that OFF is complementary to other motion modalities such as optical flow. When the proposed method is plugged into the state-of-the-art video action recognition framework, it has 96.0% accuracy on UCF-101. The code will be available online.

##### Abstract (translated by Google)
运动表示在视频中的人类行为识别中起着至关重要的作用。在这项研究中，我们引入了视频动作识别的新型紧凑型运动表示，称为光流引导特征（OFF），它使网络能够通过快速和稳健的方法提取时间信息。 OFF由光流的定义导出，并与光流正交。通过直接计算深度特征地图的逐像素时空梯度，OFF可以被嵌入到任何现有的基于CNN的视频动作识别框架中，仅需要稍微的附加成本。它使得CNN能够同时提取时空信息，特别是帧间的时间信息。这个简单而强大的想法由实验结果验证。在UCF-101上，仅通过RGB输入馈送OFF的网络达到了93.3％的竞争精度，这与两个数据流（RGB和光流）所获得的结果相当，但速度却提高了15倍。实验结果还表明，关闭是其他运动模式，如光流量的补充。当所提出的方法被插入到最先进的视频动作识别框架中时，其在UCF-101上的准确率为96.0％。该代码将在网上提供。

##### URL
[https://arxiv.org/abs/1711.11152](https://arxiv.org/abs/1711.11152)

