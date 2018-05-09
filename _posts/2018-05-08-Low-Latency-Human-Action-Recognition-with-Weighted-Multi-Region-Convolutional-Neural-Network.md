---
layout: post
title: "Low-Latency Human Action Recognition with Weighted Multi-Region Convolutional Neural Network"
date: 2018-05-08 07:57:54
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Prediction Recognition
author: Yunfeng Wang, Wengang Zhou, Qilin Zhang, Xiaotian Zhu, Houqiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Spatio-temporal contexts are crucial in understanding human actions in videos. Recent state-of-the-art Convolutional Neural Network (ConvNet) based action recognition systems frequently involve 3D spatio-temporal ConvNet filters, chunking videos into fixed length clips and Long Short Term Memory (LSTM) networks. Such architectures are designed to take advantage of both short term and long term temporal contexts, but also requires the accumulation of a predefined number of video frames (e.g., to construct video clips for 3D ConvNet filters, to generate enough inputs for LSTMs). For applications that require low-latency online predictions of fast-changing action scenes, a new action recognition system is proposed in this paper. Termed "Weighted Multi-Region Convolutional Neural Network" (WMR ConvNet), the proposed system is LSTM-free, and is based on 2D ConvNet that does not require the accumulation of video frames for 3D ConvNet filtering. Unlike early 2D ConvNets that are based purely on RGB frames and optical flow frames, the WMR ConvNet is designed to simultaneously capture multiple spatial and short term temporal cues (e.g., human poses, occurrences of objects in the background) with both the primary region (foreground) and secondary regions (mostly background). On both the UCF101 and HMDB51 datasets, the proposed WMR ConvNet achieves the state-of-the-art performance among competing low-latency algorithms. Furthermore, WMR ConvNet even outperforms the 3D ConvNet based C3D algorithm that requires video frame accumulation. In an ablation study with the optical flow ConvNet stream removed, the ablated WMR ConvNet nevertheless outperforms competing algorithms.

##### Abstract (translated by Google)
时空背景对理解视频中的人类行为至关重要。最近最先进的基于卷积神经网络（ConvNet）的动作识别系统通常涉及3D时空ConvNet滤波器，将视频分块成固定长度的片段和长时间短期存储（LSTM）网络。这样的体系结构被设计为利用短期和长期时间上下文，而且还需要预定数量的视频帧的累积（例如，构建用于3D ConvNet滤波器的视频剪辑，以产生用于LSTM的足够的输入）。对于需要低延迟在线预测快速变化动作场景的应用，本文提出了一种新的动作识别系统。定制的“加权多区域卷积神经网络”（WMR ConvNet），所提出的系统是无LSTM的，并且基于2D ConvNet，其不需要用于3D ConvNet滤波的视频帧的累积。与纯粹基于RGB帧和光流帧的早期2D ConvNets不同，WMR ConvNet旨在同时捕获多个空间和短期时间线索（例如，人体姿势，背景中物体的出现）与主要区域（前景）和次要地区（大部分是背景）。在UCF101和HMDB51数据集上，所提议的WMR ConvNet在竞争低延迟算法中实现了最先进的性能。此外，WMR ConvNet甚至胜过需要视频帧累积的基于3D ConvNet的C3D算法。在去除光流ConvNet流的消融研究中，消融的WMR ConvNet仍然优于竞争算法。

##### URL
[https://arxiv.org/abs/1805.02877](https://arxiv.org/abs/1805.02877)

##### PDF
[https://arxiv.org/pdf/1805.02877](https://arxiv.org/pdf/1805.02877)

