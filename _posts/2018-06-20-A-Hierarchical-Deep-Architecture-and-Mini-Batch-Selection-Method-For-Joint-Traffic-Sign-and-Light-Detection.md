---
layout: post
title: "A Hierarchical Deep Architecture and Mini-Batch Selection Method For Joint Traffic Sign and Light Detection"
date: 2018-06-20 21:12:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Alex D. Pon, Oles Andrienko, Ali Harakeh, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
Traffic light and sign detectors on autonomous cars are integral for road scene perception. The literature is abundant with deep learning networks that detect either lights or signs, not both, which makes them unsuitable for real-life deployment due to the limited graphics processing unit (GPU) memory and power available on embedded systems. The root cause of this issue is that no public dataset contains both traffic light and sign labels, which leads to difficulties in developing a joint detection framework. We present a deep hierarchical architecture in conjunction with a mini-batch proposal selection mechanism that allows a network to detect both traffic lights and signs from training on separate traffic light and sign datasets. Our method solves the overlapping issue where instances from one dataset are not labelled in the other dataset. We are the first to present a network that performs joint detection on traffic lights and signs. We measure our network on the Tsinghua-Tencent 100K benchmark for traffic sign detection and the Bosch Small Traffic Lights benchmark for traffic light detection and show it outperforms the existing Bosch Small Traffic light state-of-the-art method. We focus on autonomous car deployment and show our network is more suitable than others because of its low memory footprint and real-time image processing time. Qualitative results can be viewed at https://youtu.be/_YmogPzBXOw.

##### Abstract (translated by Google)
自动驾驶车辆上的交通信号灯和标志探测器是道路场景感知的必备部件文献丰富，深度学习网络能够检测灯光或标志，而不是两者，由于嵌入式系统上有限的图形处理单元（GPU）存储器和可用功率，这使得它们不适合实际部署。这个问题的根本原因是没有公共数据集同时包含交通灯和标志标签，这导致难以开发联合检测框架。我们提出了一个深层次的体系结构，结合小批量提案选择机制，允许网络检测交通信号灯和来自单独交通灯和标志数据集训练的信号。我们的方法解决了来自一个数据集的实例未在其他数据集中标记的重叠问题。我们是第一个提出在交通信号灯和标志上执行联合检测的网络。我们使用清华 - 腾讯100K基准测量了我们的交通标志检测基准和用于交通信号灯检测的博世小交通灯基准，并显示它优于现有的博世小型交通灯最先进的方法。我们专注于自动驾驶汽车的部署，并显示我们的网络比其他网络更适合，因为它的内存占用空间低，实时图像处理时间更长。定性结果可以在https://youtu.be/_YmogPzBXOw查看。

##### URL
[http://arxiv.org/abs/1806.07987](http://arxiv.org/abs/1806.07987)

##### PDF
[http://arxiv.org/pdf/1806.07987](http://arxiv.org/pdf/1806.07987)

