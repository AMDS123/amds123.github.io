---
layout: post
title: "Learning a CNN-based End-to-End Controller for a Formula SAE Racecar"
date: 2017-07-12 08:04:13
categories: arXiv_CV
tags: arXiv_CV
author: Skanda Koppula
mathjax: true
---

* content
{:toc}

##### Abstract
We present a set of CNN-based end-to-end models for controls of a Formula SAE racecar, along with various benchmarking and visualization tools to understand model performance. We tackled three main problems in the context of cone-delineated racetrack driving: (1) discretized steering, which translates a first-person frame along to the track to a predicted steering direction. (2) real-value steering, which translates a frame view to a real-value steering angle, and (3) a network design for predicting brake and throttle. We demonstrate high accuracy on our discretization task, low theoretical testing errors with our model for real-value steering, and a starting point for future work regarding a controller for our vehicle's brake and throttle. Timing benchmarks suggests that the networks we propose have the latency and throughput required for real-time controllers, when run on GPU-enabled hardware.

##### Abstract (translated by Google)
我们提供了一套基于CNN的端到端模型，用于控制一辆Formula SAE赛车，以及各种基准测试和可视化工具来了解模型性能。我们在锥形赛道驾驶的情况下解决了三个主要问题：（1）离散化的转向，其将第一人称框架沿着轨道转换成预测的转向方向。 （2）将车架视图转化为实际转向角的实值转向，以及（3）用于预测制动和节气门的网络设计。我们的离散化任务表现出高精度，我们的真实值转向模型的理论测试误差较低，以及未来我们的车辆制动和油门控制器的工作起点。时序基准测试表明，我们提出的网络具有在启用GPU的硬件上运行时实时控制器所需的延迟和吞吐量。

##### URL
[https://arxiv.org/abs/1708.02215](https://arxiv.org/abs/1708.02215)

##### PDF
[https://arxiv.org/pdf/1708.02215](https://arxiv.org/pdf/1708.02215)

