---
layout: post
title: "Fast Scene Understanding for Autonomous Driving"
date: 2017-08-08 16:31:52
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Davy Neven, Bert De Brabandere, Stamatios Georgoulis, Marc Proesmans, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Most approaches for instance-aware semantic labeling traditionally focus on accuracy. Other aspects like runtime and memory footprint are arguably as important for real-time applications such as autonomous driving. Motivated by this observation and inspired by recent works that tackle multiple tasks with a single integrated architecture, in this paper we present a real-time efficient implementation based on ENet that solves three autonomous driving related tasks at once: semantic scene segmentation, instance segmentation and monocular depth estimation. Our approach builds upon a branched ENet architecture with a shared encoder but different decoder branches for each of the three tasks. The presented method can run at 21 fps at a resolution of 1024x512 on the Cityscapes dataset without sacrificing accuracy compared to running each task separately.

##### Abstract (translated by Google)
实例感知语义标注的大多数方法传统上都注重准确性。运行时间和内存占用等其他方面对于实时应用程序（如自主驾驶）来说也是非常重要的。受此观察和启发，最近的作品采用单一集成架构处理多个任务，本文中，我们提出了基于ENet的实时高效实现方法，可以同时解决三个自主驾驶相关任务：语义场景分割，实例分割和单眼深度估计。我们的方法建立在共享编码器的分支ENet架构上，但是对于三个任务中的每一个来说，都有不同的解码器分支。与单独运行每个任务相比，所提出的方法可以在城市风景数据集上以1024x512的分辨率以21fps运行，而不会牺牲准确性。

##### URL
[https://arxiv.org/abs/1708.02550](https://arxiv.org/abs/1708.02550)

##### PDF
[https://arxiv.org/pdf/1708.02550](https://arxiv.org/pdf/1708.02550)

