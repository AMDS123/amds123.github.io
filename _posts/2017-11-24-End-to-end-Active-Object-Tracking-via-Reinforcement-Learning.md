---
layout: post
title: "End-to-end Active Object Tracking via Reinforcement Learning"
date: 2017-11-24 15:11:45
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Reinforcement_Learning Object_Tracking RNN
author: Wenhan Luo, Peng Sun, Fangwei Zhong, Wei Liu, Yizhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an active object tracking approach, which provides a tracking solution simultaneously addressing tracking and camera control. Crucially, these two tasks are tackled in an end-to-end manner via reinforcement learning. Specifically, a ConvNet-LSTM function approximator is adopted, which takes as input only visual observations (i.e., frame sequences) and directly outputs camera motions (e.g., move forward, turn left, etc.). The tracker, regarded as an agent, is trained with the A3C algorithm, where we harness environment augmentation techniques and a customized reward function to encourage robust object tracking. We carry out experiments on two types of virtual environments, ViZDoom and Unreal Engine. The yielded tracker can automatically pay attention to the most likely object in the initial frame and perform tracking subsequently, not requiring a manual bounding box as initialization. Moreover, our approach shows a good generalization ability when performing tracking in the case of unseen object moving path, object appearance, background and distracting object. The tracker can even restore tracking once it occasionally loses the target.

##### Abstract (translated by Google)
在本文中，我们提出了一种主动对象跟踪方法，它提供了一个同时解决跟踪和摄像机控制的跟踪解决方案。至关重要的是，这两项任务是通过强化学习以端对端的方式解决的。具体地，采用ConvNet-LSTM函数逼近器，其仅将视觉观察（即，帧序列）作为输入，并直接输出相机运动（例如向前移动，向左转等）。作为代理人的跟踪器使用A3C算法进行训练，我们利用环境增强技术和定制奖励功能来鼓励强大的对象跟踪。我们在两种类型的虚拟环境，ViZDoom和虚幻引擎上进行实验。产生的跟踪器可以自动关注最初帧中最可能的对象，并随后执行跟踪，不需要手动边界框作为初始化。另外，在看不见物体移动路径，物体外观，背景和分散物体的情况下，我们的方法在进行跟踪时显示出良好的泛化能力。一旦偶尔丢失目标，跟踪器甚至可以恢复跟踪。

##### URL
[https://arxiv.org/abs/1705.10561](https://arxiv.org/abs/1705.10561)

##### PDF
[https://arxiv.org/pdf/1705.10561](https://arxiv.org/pdf/1705.10561)

