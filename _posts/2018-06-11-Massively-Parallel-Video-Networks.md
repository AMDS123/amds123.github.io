---
layout: post
title: "Massively Parallel Video Networks"
date: 2018-06-11 08:46:51
categories: arXiv_CV
tags: arXiv_CV Video_Caption Action_Recognition CNN Recognition
author: Joao Carreira, Viorica Patraucean, Laurent Mazare, Andrew Zisserman, Simon Osindero
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a class of causal video understanding models that aims to improve efficiency of video processing by maximising throughput, minimising latency, and reducing the number of clock cycles. Leveraging operation pipelining and multi-rate clocks, these models perform a minimal amount of computation (e.g. as few as four convolutional layers) for each frame per timestep to produce an output. The models are still very deep, with dozens of such operations being performed but in a pipelined fashion that enables depth-parallel computation. We illustrate the proposed principles by applying them to existing image architectures and analyse their behaviour on two video tasks: action recognition and human keypoint localisation. The results show that a significant degree of parallelism, and implicitly speedup, can be achieved with little loss in performance.

##### Abstract (translated by Google)
我们引入了一类因果视频理解模型，旨在通过最大化吞吐量，最小化延迟以及减少时钟周期数来提高视频处理的效率。利用操作流水线和多速率时钟，这些模型对每个时间步每个帧执行最少量的计算（例如少至四个卷积层）以产生输出。这些模型仍然非常深入，有数十个这样的操作正在执行中，但采用流水线方式进行深度并行计算。我们通过将它们应用于现有的图像体系结构并分析它们在两个视频任务上的行为来说明提出的原则：动作识别和人类关键点本地化。结果表明，在很少的性能损失下，可以实现显着的并行性，并且可以实现隐式加速。

##### URL
[http://arxiv.org/abs/1806.03863](http://arxiv.org/abs/1806.03863)

##### PDF
[http://arxiv.org/pdf/1806.03863](http://arxiv.org/pdf/1806.03863)

