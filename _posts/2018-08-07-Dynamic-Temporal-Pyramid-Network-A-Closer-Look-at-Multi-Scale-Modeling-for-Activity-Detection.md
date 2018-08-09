---
layout: post
title: "Dynamic Temporal Pyramid Network: A Closer Look at Multi-Scale Modeling for Activity Detection"
date: 2018-08-07 20:02:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Da Zhang, Xiyang Dai, Yuan-Fang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing instances at different scales simultaneously is a fundamental challenge in visual detection problems. While spatial multi-scale modeling has been well studied in object detection, how to effectively apply a multi-scale architecture to temporal models for activity detection is still under-explored. In this paper, we identify three unique challenges that need to be specifically handled for temporal activity detection compared to its spatial counterpart. To address all these issues, we propose Dynamic Temporal Pyramid Network (DTPN), a new activity detection framework with a multi-scale pyramidal architecture featuring three novel designs: (1) We sample input video frames dynamically with varying frame per seconds (FPS) to construct a natural pyramidal input for video of an arbitrary length. (2) We design a two-branch multi-scale temporal feature hierarchy to deal with the inherent temporal scale variation of activity instances. (3) We further exploit the temporal context of activities by appropriately fusing multi-scale feature maps, and demonstrate that both local and global temporal contexts are important. By combining all these components into a uniform network, we end up with a single-shot activity detector involving single-pass inferencing and end-to-end training. Extensive experiments show that the proposed DTPN achieves state-of-the-art performance on the challenging ActvityNet dataset.

##### Abstract (translated by Google)
同时识别不同尺度的实例是视觉检测问题的基本挑战。虽然在对象检测中已经很好地研究了空间多尺度建模，但是如何有效地将多尺度架构应用于用于活动检测的时间模型仍然未得到充分研究。在本文中，我们确定了与空间对应物相比，需要针对时间活动检测专门处理的三个独特挑战。为了解决所有这些问题，我们提出了动态时间金字塔网络（DTPN），这是一种新的活动检测框架，具有多尺度金字塔结构，具有三种新颖的设计：（1）我们以每秒不同的帧（FPS）动态采样输入视频帧构建任意长度视频的自然金字塔输入。 （2）我们设计了一个双分支多尺度时间特征层次来处理活动实例的固有时间尺度变化。 （3）我们通过适当融合多尺度特征图进一步利用活动的时间背景，并证明局部和全局时间上下文都很重要。通过将所有这些组件组合成一个统一的网络，我们最终得到了一个单次活动检测器，包括单通道推理和端到端培训。大量实验表明，所提出的DTPN在具有挑战性的ActvityNet数据集上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1808.02536](http://arxiv.org/abs/1808.02536)

##### PDF
[http://arxiv.org/pdf/1808.02536](http://arxiv.org/pdf/1808.02536)

