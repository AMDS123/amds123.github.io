---
layout: post
title: "Deep Tracking: Seeing Beyond Seeing Using Recurrent Neural Networks"
date: 2016-03-08 22:09:05
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Object_Tracking RNN Deep_Learning
author: Peter Ondruska, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents to the best of our knowledge the first end-to-end object tracking approach which directly maps from raw sensor input to object tracks in sensor space without requiring any feature engineering or system identification in the form of plant or sensor models. Specifically, our system accepts a stream of raw sensor data at one end and, in real-time, produces an estimate of the entire environment state at the output including even occluded objects. We achieve this by framing the problem as a deep learning task and exploit sequence models in the form of recurrent neural networks to learn a mapping from sensor measurements to object tracks. In particular, we propose a learning method based on a form of input dropout which allows learning in an unsupervised manner, only based on raw, occluded sensor data without access to ground-truth annotations. We demonstrate our approach using a synthetic dataset designed to mimic the task of tracking objects in 2D laser data -- as commonly encountered in robotics applications -- and show that it learns to track many dynamic objects despite occlusions and the presence of sensor noise.

##### Abstract (translated by Google)
本文介绍了我们所知道的第一个端到端的对象跟踪方法，它直接从原始传感器输入映射到传感器空间中的对象轨迹，而不需要以工厂或传感器模型的形式进行任何特征工程或系统识别。具体而言，我们的系统在一端接收原始传感器数据流，并实时地在输出端产生整个环境状态的估计，甚至包括被遮挡的对象。我们通过将问题定义为深度学习任务并利用递归神经网络形式的序列模型来学习从传感器测量到对象轨迹的映射来实现这一点。特别是，我们提出了一种基于输入丢失形式的学习方法，它允许以无监督的方式进行学习，仅基于原始的，被遮挡的传感器数据而无需访问地面真实性注释。我们展示了我们的方法，使用设计用来模仿跟踪二维激光数据中的对象的任务 - 就像在机器人应用中常见的那样 - 并且显示它学习跟踪许多动态对象，尽管有遮挡和传感器噪声的存在。

##### URL
[https://arxiv.org/abs/1602.00991](https://arxiv.org/abs/1602.00991)

##### PDF
[https://arxiv.org/pdf/1602.00991](https://arxiv.org/pdf/1602.00991)

