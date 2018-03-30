---
layout: post
title: "Context-aware Deep Feature Compression for High-speed Visual Tracking"
date: 2018-03-28 11:38:12
categories: arXiv_CV
tags: arXiv_CV Tracking Relation
author: Jongwon Choi, Hyung Jin Chang, Tobias Fischer, Sangdoo Yun, Kyuewang Lee, Jiyeoup Jeong, Yiannis Demiris, Jin Young Choi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new context-aware correlation filter based tracking framework to achieve both high computational speed and state-of-the-art performance among real-time trackers. The major contribution to the high computational speed lies in the proposed deep feature compression that is achieved by a context-aware scheme utilizing multiple expert auto-encoders; a context in our framework refers to the coarse category of the tracking target according to appearance patterns. In the pre-training phase, one expert auto-encoder is trained per category. In the tracking phase, the best expert auto-encoder is selected for a given target, and only this auto-encoder is used. To achieve high tracking performance with the compressed feature map, we introduce extrinsic denoising processes and a new orthogonality loss term for pre-training and fine-tuning of the expert auto-encoders. We validate the proposed context-aware framework through a number of experiments, where our method achieves a comparable performance to state-of-the-art trackers which cannot run in real-time, while running at a significantly fast speed of over 100 fps.

##### Abstract (translated by Google)
我们提出了一种新的基于上下文感知相关滤波器的跟踪框架，以实现实时跟踪器之间的高计算速度和最先进的性能。对高计算速度的主要贡献在于所提出的深度特征压缩，其通过利用多个专家自动编码器的情境感知方案来实现;我们框架中的上下文是指根据外观模式的跟踪目标的粗略类别。在预训练阶段，每个类别训练一个专家自动编码器。在跟踪阶段，为给定目标选择最佳专家自动编码器，并且仅使用该自动编码器。为了实现压缩特征映射的高跟踪性能，我们引入了外部去噪过程和新的正交性损失项，用于专业自动编码器的预训练和微调。我们通过大量实验来验证所提出的情景感知框架，在这些实验中，我们的方法达到了与不能实时运行的最先进跟踪器相当的性能，同时以超过100 fps的速度以极快的速度运行。

##### URL
[https://arxiv.org/abs/1803.10537](https://arxiv.org/abs/1803.10537)

##### PDF
[https://arxiv.org/pdf/1803.10537](https://arxiv.org/pdf/1803.10537)

