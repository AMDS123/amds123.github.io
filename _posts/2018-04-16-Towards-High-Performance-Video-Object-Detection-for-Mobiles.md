---
layout: post
title: "Towards High Performance Video Object Detection for Mobiles"
date: 2018-04-16 17:59:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Xizhou Zhu, Jifeng Dai, Xingchi Zhu, Yichen Wei, Lu Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success of video object detection on Desktop GPUs, its architecture is still far too heavy for mobiles. It is also unclear whether the key principles of sparse feature propagation and multi-frame feature aggregation apply at very limited computational resources. In this paper, we present a light weight network architecture for video object detection on mobiles. Light weight image object detector is applied on sparse key frames. A very small network, Light Flow, is designed for establishing correspondence across frames. A flow-guided GRU module is designed to effectively aggregate features on key frames. For non-key frames, sparse feature propagation is performed. The whole network can be trained end-to-end. The proposed system achieves 60.2% mAP score at speed of 25.6 fps on mobiles (e.g., HuaWei Mate 8).

##### Abstract (translated by Google)
尽管最近在桌面GPU上成功实现了视频对象检测，但它的体系结构对手机来说仍然过于沉重。稀疏特征传播和多帧特征聚合的关键原理是否适用于非常有限的计算资源也不清楚。在本文中，我们提出了一个轻量级网络体系结构，用于在手机上进行视频对象检测。轻量级图像对象检测器应用于稀疏关键帧。一个非常小的网络Light Flow旨在跨帧建立对应关系。流引导的GRU模块旨在有效地聚合关键帧上的特征。对于非关键帧，执行稀疏特征传播。整个网络可以进行端到端的培训。所提出的系统在移动设备（例如，HuaWei Mate 8）上以25.6fps的速度获得60.2％的mAP分数。

##### URL
[https://arxiv.org/abs/1804.05830](https://arxiv.org/abs/1804.05830)

##### PDF
[https://arxiv.org/pdf/1804.05830](https://arxiv.org/pdf/1804.05830)

