---
layout: post
title: "NoScope: Optimizing Neural Network Queries over Video at Scale"
date: 2017-08-08 21:34:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Classification Detection
author: Daniel Kang, John Emmons, Firas Abuzaid, Peter Bailis, Matei Zaharia
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in computer vision-in the form of deep neural networks-have made it possible to query increasing volumes of video data with high accuracy. However, neural network inference is computationally expensive at scale: applying a state-of-the-art object detector in real time (i.e., 30+ frames per second) to a single video requires a $4000 GPU. In response, we present NoScope, a system for querying videos that can reduce the cost of neural network video analysis by up to three orders of magnitude via inference-optimized model search. Given a target video, object to detect, and reference neural network, NoScope automatically searches for and trains a sequence, or cascade, of models that preserves the accuracy of the reference network but is specialized to the target video and are therefore far less computationally expensive. NoScope cascades two types of models: specialized models that forego the full generality of the reference model but faithfully mimic its behavior for the target video and object; and difference detectors that highlight temporal differences across frames. We show that the optimal cascade architecture differs across videos and objects, so NoScope uses an efficient cost-based optimizer to search across models and cascades. With this approach, NoScope achieves two to three order of magnitude speed-ups (265-15,500x real-time) on binary classification tasks over fixed-angle webcam and surveillance video while maintaining accuracy within 1-5% of state-of-the-art neural networks.

##### Abstract (translated by Google)
计算机视觉方面的最新进展（以深度神经网络的形式）使得能够高精度地查询越来越多的视频数据。然而，神经网络推断在规模上在计算上是昂贵的：对一个视频应用实时（即，每秒30+帧）的现代物体检测器需要4000美元的GPU。作为回应，我们提出了NoScope，这是一个查询视频的系统，可以通过推理优化的模型搜索将神经网络视频分析的成本降低三个数量级。给定一个目标视频，目标来检测，并参考神经网络，NoScope自动搜索和训练序列，或级联的模型，保留参考网络的准确性，但专门针对目标视频，因此远不太昂贵的计算成本。 NoScope级联两种类型的模型：专门的模型，放弃参考模型的完整通用性，但忠实地模仿目标视频和对象的行为;以及突出跨帧的时间差异的差异检测器。我们展示了视频和对象的最佳级联架构不同，因此NoScope使用高效的基于成本的优化器来搜索模型和级联。通过这种方法，NoScope在固定角度的摄像头和监控视频上进行二进制分类任务时，实现了两到三个数量级的加速（265-15,500x实时），同时保持精度在1-5％的状态-art神经网络。

##### URL
[https://arxiv.org/abs/1703.02529](https://arxiv.org/abs/1703.02529)

##### PDF
[https://arxiv.org/pdf/1703.02529](https://arxiv.org/pdf/1703.02529)

