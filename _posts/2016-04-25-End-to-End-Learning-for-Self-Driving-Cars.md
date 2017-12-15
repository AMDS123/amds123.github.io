---
layout: post
title: "End to End Learning for Self-Driving Cars"
date: 2016-04-25 16:03:56
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Mariusz Bojarski, Davide Del Testa, Daniel Dworakowski, Bernhard Firner, Beat Flepp, Prasoon Goyal, Lawrence D. Jackel, Mathew Monfort, Urs Muller, Jiakai Zhang, Xin Zhang, Jake Zhao, Karol Zieba
mathjax: true
---

* content
{:toc}

##### Abstract
We trained a convolutional neural network (CNN) to map raw pixels from a single front-facing camera directly to steering commands. This end-to-end approach proved surprisingly powerful. With minimum training data from humans the system learns to drive in traffic on local roads with or without lane markings and on highways. It also operates in areas with unclear visual guidance such as in parking lots and on unpaved roads. The system automatically learns internal representations of the necessary processing steps such as detecting useful road features with only the human steering angle as the training signal. We never explicitly trained it to detect, for example, the outline of roads. Compared to explicit decomposition of the problem, such as lane marking detection, path planning, and control, our end-to-end system optimizes all processing steps simultaneously. We argue that this will eventually lead to better performance and smaller systems. Better performance will result because the internal components self-optimize to maximize overall system performance, instead of optimizing human-selected intermediate criteria, e.g., lane detection. Such criteria understandably are selected for ease of human interpretation which doesn't automatically guarantee maximum system performance. Smaller networks are possible because the system learns to solve the problem with the minimal number of processing steps. We used an NVIDIA DevBox and Torch 7 for training and an NVIDIA DRIVE(TM) PX self-driving car computer also running Torch 7 for determining where to drive. The system operates at 30 frames per second (FPS).

##### Abstract (translated by Google)
我们训练了一个卷积神经网络（CNN），将单个前置摄像头的原始像素直接映射到转向命令。这种端到端的方法证明是非常强大的。利用来自人类的最小训练数据，系统学习在具有或不具有车道标记的本地道路和高速公路上驾驶交通。它也在视觉引导不明确的地方，例如停车场和未铺设的道路上运行。系统自动学习必要的处理步骤的内部表示，例如仅以人的转向角度作为训练信号来检测有用的道路特征。例如，我们从未明确地训练它检测道路的轮廓。与明确分解问题（如车道标记检测，路径规划和控制）相比，我们的端到端系统同时优化所有处理步骤。我们认为这将最终导致更好的性能和更小的系统。由于内部组件自我优化以最大化整体系统性能，而不是优化人选中间标准（例如车道检测），所以会导致更好的性能。这样的标准是可以理解的选择，以便于人的解释，而不会自动保证最大的系统性能。较小的网络是可能的，因为系统学习用最少的处理步骤来解决问题。我们使用NVIDIA DevBox和Torch 7进行培训，还使用了一台运行Torch 7的NVIDIA DRIVE（TM）PX自驾车车载电脑，以确定驾驶位置。系统以每秒30帧（FPS）的速度运行。

##### URL
[https://arxiv.org/abs/1604.07316](https://arxiv.org/abs/1604.07316)

##### PDF
[https://arxiv.org/pdf/1604.07316](https://arxiv.org/pdf/1604.07316)

