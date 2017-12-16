---
layout: post
title: "UCT: Learning Unified Convolutional Networks for Real-time Visual Tracking"
date: 2017-11-10 09:18:06
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Optimization
author: Zheng Zhu, Guan Huang, Wei Zou, Dalong Du, Chang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNN) based tracking approaches have shown favorable performance in recent benchmarks. Nonetheless, the chosen CNN features are always pre-trained in different task and individual components in tracking systems are learned separately, thus the achieved tracking performance may be suboptimal. Besides, most of these trackers are not designed towards real-time applications because of their time-consuming feature extraction and complex optimization details.In this paper, we propose an end-to-end framework to learn the convolutional features and perform the tracking process simultaneously, namely, a unified convolutional tracker (UCT). Specifically, The UCT treats feature extractor and tracking process both as convolution operation and trains them jointly, enabling learned CNN features are tightly coupled to tracking process. In online tracking, an efficient updating method is proposed by introducing peak-versus-noise ratio (PNR) criterion, and scale changes are handled efficiently by incorporating a scale branch into network. The proposed approach results in superior tracking performance, while maintaining real-time speed. The standard UCT and UCT-Lite can track generic objects at 41 FPS and 154 FPS without further optimization, respectively. Experiments are performed on four challenging benchmark tracking datasets: OTB2013, OTB2015, VOT2014 and VOT2015, and our method achieves state-of-the-art results on these benchmarks compared with other real-time trackers.

##### Abstract (translated by Google)
基于卷积神经网络（CNN）的跟踪方法在近期的基准测试中表现出良好的性能。尽管如此，所选择的CNN特征总是在不同的任务中被预先训练，并且跟踪系统中的各个组件被单独学习，因此实现的跟踪性能可能是不理想的。另外，这些跟踪器中的大多数并不是针对实时应用而设计的，因为它们耗时的特征提取和复杂的优化细节。本文提出了一个端到端的框架来学习卷积特征并执行跟踪过程同时也就是统一的卷积跟踪器（UCT）。具体而言，UCT将特征提取和跟踪过程都视为卷积操作并联合训练，使学习到的CNN特征与跟踪过程紧密结合。在在线跟踪中，通过引入峰值噪声比（PNR）准则，提出了一种有效的更新方法，并且通过将规模分支并入网络来有效处理规模变化。所提出的方法导致优异的跟踪性能，同时保持实时速度。标准UCT和UCT-Lite可以分别在41 FPS和154 FPS下跟踪通用对象，而无需进一步优化。在四个具有挑战性的基准跟踪数据集上进行实验：OTB2013，OTB2015，VOT2014和VOT2015，与其他实时跟踪器相比，我们的方法在这些基准测试中达到了最新的结果。

##### URL
[https://arxiv.org/abs/1711.04661](https://arxiv.org/abs/1711.04661)

##### PDF
[https://arxiv.org/pdf/1711.04661](https://arxiv.org/pdf/1711.04661)

