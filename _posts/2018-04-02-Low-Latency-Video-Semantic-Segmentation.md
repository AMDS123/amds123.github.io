---
layout: post
title: "Low-Latency Video Semantic Segmentation"
date: 2018-04-02 03:47:51
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction
author: Yule Li, Jianping Shi, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen remarkable progress in semantic segmentation. Yet, it remains a challenging task to apply segmentation techniques to video-based applications. Specifically, the high throughput of video streams, the sheer cost of running fully convolutional networks, together with the low-latency requirements in many real-world applications, e.g. autonomous driving, present a significant challenge to the design of the video segmentation framework. To tackle this combined challenge, we develop a framework for video semantic segmentation, which incorporates two novel components: (1) a feature propagation module that adaptively fuses features over time via spatially variant convolution, thus reducing the cost of per-frame computation; and (2) an adaptive scheduler that dynamically allocate computation based on accuracy prediction. Both components work together to ensure low latency while maintaining high segmentation quality. On both Cityscapes and CamVid, the proposed framework obtained competitive performance compared to the state of the art, while substantially reducing the latency, from 360 ms to 119 ms.

##### Abstract (translated by Google)
近年来语义分割取得了显着进展。然而，将分割技术应用于基于视频的应用程序仍然是一项具有挑战性的任务。具体而言，视频流的高吞吐量，完全卷积网络的运行成本以及许多真实世界应用中的低延迟需求（例如，自动驾驶，对视频分割框架的设计提出了重大挑战。为了解决这个综合挑战，我们开发了一个视频语义分割框架，它包含两个新颖的组件：（1）一个特征传播模块，通过空间变化卷积自适应地融合特征，从而降低每帧计算的成本;和（2）基于精度预测动态分配计算的自适应调度器。两个组件一起工作以确保低延迟，同时保持高分割质量。在Cityscapes和CamVid上，与现有技术水平相比，所提议的框架获得了有竞争力的表现，同时将等待时间从360ms降至119ms。

##### URL
[http://arxiv.org/abs/1804.00389](http://arxiv.org/abs/1804.00389)

##### PDF
[http://arxiv.org/pdf/1804.00389](http://arxiv.org/pdf/1804.00389)

