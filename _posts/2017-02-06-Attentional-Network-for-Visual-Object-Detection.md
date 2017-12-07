---
layout: post
title: "Attentional Network for Visual Object Detection"
date: 2017-02-06 00:50:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Reinforcement_Learning Detection
author: Kota Hara, Ming-Yu Liu, Oncel Tuzel, Amir-massoud Farahmand
mathjax: true
---

* content
{:toc}

##### Abstract
We propose augmenting deep neural networks with an attention mechanism for the visual object detection task. As perceiving a scene, humans have the capability of multiple fixation points, each attended to scene content at different locations and scales. However, such a mechanism is missing in the current state-of-the-art visual object detection methods. Inspired by the human vision system, we propose a novel deep network architecture that imitates this attention mechanism. As detecting objects in an image, the network adaptively places a sequence of glimpses of different shapes at different locations in the image. Evidences of the presence of an object and its location are extracted from these glimpses, which are then fused for estimating the object class and bounding box coordinates. Due to lacks of ground truth annotations of the visual attention mechanism, we train our network using a reinforcement learning algorithm with policy gradients. Experiment results on standard object detection benchmarks show that the proposed network consistently outperforms the baseline networks that does not model the attention mechanism.

##### Abstract (translated by Google)
我们提出增强深层神经网络的视觉对象检测任务的注意机制。当感知一个场景时，人类具有多个注视点的能力，每个注视点在不同的位置和尺度上注视场景内容。但是，目前最先进的视觉对象检测方法中缺少这种机制。受到人类视觉系统的启发，我们提出了一种模仿这种注意机制的新型深度网络体系结构。当检测图像中的对象时，网络自适应地在图像中的不同位置放置一系列不同形状的镜头。从这些瞥见中提取对象存在的证据及其位置，然后将其融合以估计对象类别和边界框坐标。由于缺乏视觉注意机制的地面真实性注释，我们使用具有策略梯度的强化学习算法来训练我们的网络。标准对象检测基准的实验结果表明，所提出的网络始终优于没有对关注机制建模的基线网络。

##### URL
[https://arxiv.org/abs/1702.01478](https://arxiv.org/abs/1702.01478)

##### PDF
[https://arxiv.org/pdf/1702.01478](https://arxiv.org/pdf/1702.01478)

