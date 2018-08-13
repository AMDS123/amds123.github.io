---
layout: post
title: "End-to-end Active Object Tracking and Its Real-world Deployment via Reinforcement Learning"
date: 2018-08-10 04:04:19
categories: arXiv_CV
tags: arXiv_CV Tracking Reinforcement_Learning Object_Tracking RNN Prediction
author: Wenhan Luo, Peng Sun, Fangwei Zhong, Wei Liu, Tong Zhang, Yizhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We study active object tracking, where a tracker takes visual observations (i.e., frame sequences) as inputs and produces the corresponding camera control signals as outputs (e.g., move forward, turn left, etc.). Conventional methods tackle tracking and camera control tasks separately, and the resulting system is difficult to tune jointly. Such an approach also requires significant human efforts for image labeling and expensive trial-and-error system tuning in real-world. To address these issues, we propose, in this paper, an end-to-end solution via deep reinforcement learning. A ConvNet-LSTM function approximator is adopted for the direct frame-to-action prediction. We further propose an environment augmentation technique and a customized reward function which are crucial for successful training. The tracker trained in simulators (ViZDoom and Unreal Engine) demonstrates good generalization behaviors in the case of unseen object moving paths, unseen object appearances, unseen backgrounds, and distracting objects. The system is robust and can restore tracking after occasional lost of the target being tracked. We also find that the tracking ability, obtained solely from simulators, can potentially transfer to real-world scenarios. We demonstrate successful examples of such transfer, via experiments over the VOT dataset and the deployment of a real-world robot using the proposed active tracker trained in simulation.

##### Abstract (translated by Google)
我们研究活动对象跟踪，其中跟踪器将视觉观察（即，帧序列）作为输入并产生相应的摄像机控制信号作为输出（例如，向前移动，向左转，等等）。传统方法分别处理跟踪和摄像机控制任务，并且所得系统难以共同调整。这种方法还需要在现实世界中进行图像标记和昂贵的反复试验系统调整。为了解决这些问题，我们在本文中提出了通过深度强化学习的端到端解决方案。采用ConvNet-LSTM函数逼近器进行直接帧到动作预测。我们进一步提出了一种环境增强技术和定制的奖励功能，这对于成功的培训至关重要。在模拟器（ViZDoom和虚幻引擎）中训练的跟踪器在看不见的物体移动路径，看不见的物体外观，看不见的背景和分散注意力的物体的情况下表现出良好的泛化行为。该系统非常强大，可以在偶尔丢失被跟踪的目标后恢复跟踪。我们还发现，仅从模拟器获得的跟踪能力可能会转移到现实世界的场景中。我们通过VOT数据集上的实验和使用在模拟中训练的拟议主动跟踪器部署真实世界机器人，展示了这种传输的成功示例。

##### URL
[http://arxiv.org/abs/1808.03405](http://arxiv.org/abs/1808.03405)

##### PDF
[http://arxiv.org/pdf/1808.03405](http://arxiv.org/pdf/1808.03405)

