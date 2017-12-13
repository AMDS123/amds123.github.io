---
layout: post
title: "Using GPI-2 for Distributed Memory Paralleliziation of the Caffe Toolbox to Speed up Deep Neural Network Training"
date: 2017-08-18 12:24:45
categories: arXiv_CV
tags: arXiv_CV Face
author: Martin Kuehn, Janis Keuper, Franz-Josef Pfreundt
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Network (DNN) are currently of great inter- est in research and application. The training of these net- works is a compute intensive and time consuming task. To reduce training times to a bearable amount at reasonable cost we extend the popular Caffe toolbox for DNN with an efficient distributed memory communication pattern. To achieve good scalability we emphasize the overlap of computation and communication and prefer fine granu- lar synchronization patterns over global barriers. To im- plement these communication patterns we rely on the the Global address space Programming Interface version 2 (GPI-2) communication library. This interface provides a light-weight set of asynchronous one-sided communica- tion primitives supplemented by non-blocking fine gran- ular data synchronization mechanisms. Therefore, Caf- feGPI is the name of our parallel version of Caffe. First benchmarks demonstrate better scaling behavior com- pared with other extensions, e.g., the Intel TM Caffe. Even within a single symmetric multiprocessing machine with four graphics processing units, the CaffeGPI scales bet- ter than the standard Caffe toolbox. These first results demonstrate that the use of standard High Performance Computing (HPC) hardware is a valid cost saving ap- proach to train large DDNs. I/O is an other bottleneck to work with DDNs in a standard parallel HPC setting, which we will consider in more detail in a forthcoming paper.

##### Abstract (translated by Google)
深度神经网络（DNN）目前在研究和应用上非常有用。这些网络的培训是一个计算密集和耗时的任务。为了将培训时间以合理的成本减少到可承受的数量，我们扩展了流行的用于DNN的Caffe工具箱，其具有高效的分布式存储器通信模式。为了获得良好的可扩展性，我们强调计算和通信的重叠，并且偏好细粒度的同步模式而不是全局障碍。为了实现这些通信模式，我们依靠全局地址空间编程接口版本2（GPI-2）通信库。该接口提供了一套轻量级的异步单向通信原语，并辅以非阻塞的精细大小数据同步机制。因此，Caf-feGPI是我们平行版Caffe的名字。与其他扩展（例如英特尔TM Caffe）相比，第一个基准测试表现出更好的缩放行为。即使在具有四个图形处理单元的单个对称多处理机器中，CaffeGPI也会比标准的Caffe工具箱更好地缩放。这些第一个结果表明，使用标准的高性能计算（HPC）硬件是一种有效的节约成本的方法来培训大型的DDN。在标准的并行HPC环境中，I / O是与DDN一起工作的另一个瓶颈，我们将在即将发表的论文中更详细地讨论这个问题。

##### URL
[https://arxiv.org/abs/1706.00095](https://arxiv.org/abs/1706.00095)

##### PDF
[https://arxiv.org/pdf/1706.00095](https://arxiv.org/pdf/1706.00095)

