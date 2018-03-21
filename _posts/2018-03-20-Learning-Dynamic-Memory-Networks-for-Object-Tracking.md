---
layout: post
title: "Learning Dynamic Memory Networks for Object Tracking"
date: 2018-03-20 06:20:15
categories: arXiv_CV
tags: arXiv_CV Dynamic_Memory_Network Attention Tracking Object_Tracking RNN Detection Memory_Networks
author: Tianyu Yang, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Template-matching methods for visual tracking have gained popularity recently due to their comparable performance and fast speed. However, they lack effective ways to adapt to changes in the target object's appearance, making their tracking accuracy still far from state-of-the-art. In this paper, we propose a dynamic memory network to adapt the template to the target's appearance variations during tracking. An LSTM is used as a memory controller, where the input is the search feature map and the outputs are the control signals for the reading and writing process of the memory block. As the location of the target is at first unknown in the search feature map, an attention mechanism is applied to concentrate the LSTM input on the potential target. To prevent aggressive model adaptivity, we apply gated residual template learning to control the amount of retrieved memory that is used to combine with the initial template. Unlike tracking-by-detection methods where the object's information is maintained by the weight parameters of neural networks, which requires expensive online fine-tuning to be adaptable, our tracker runs completely feed-forward and adapts to the target's appearance changes by updating the external memory. Moreover, the capacity of our model is not determined by the network size as with other trackers -- the capacity can be easily enlarged as the memory requirements of a task increase, which is favorable for memorizing long-term object information. Extensive experiments on OTB and VOT demonstrates that our tracker MemTrack performs favorably against state-of-the-art tracking methods while retaining real-time speed of 50 fps.

##### Abstract (translated by Google)
由于具有可比较的性能和快速的速度，用于视觉跟踪的模板匹配方法近来获得了普及。然而，它们缺乏适应目标物体外观变化的有效方法，使得它们的跟踪精度与最新技术相差甚远。在本文中，我们提出了一个动态记忆网络，以便在跟踪过程中使模板适应目标的外观变化。 LSTM用作存储器控制器，其中输入是搜索特征映射，并且输出是用于存储器块的读取和写入过程的控制信号。由于目标的位置在搜索特征图中首先是未知的，因此应用关注机制将LSTM输入集中在潜在目标上。为了防止积极的模型自适应性，我们应用门控残留模板学习来控制用于与初始模板结合的检索内存量。与通过神经网络的权重参数来维护对象的信息不同的跟踪检测方法不同，我们的跟踪器完全前馈运行，并且通过更新外部参数来适应目标的外观变化记忆。而且，我们模型的容量并不像其他跟踪器那样由网络大小决定 - 随着任务内存需求的增加，容量可以容易地扩大，这有利于记忆长期目标信息。在OTB和VOT上的大量实验表明，我们的跟踪器MemTrack在保持50 fps的实时速度的同时，对最先进的跟踪方法表现优异。

##### URL
[http://arxiv.org/abs/1803.07268](http://arxiv.org/abs/1803.07268)

##### PDF
[http://arxiv.org/pdf/1803.07268](http://arxiv.org/pdf/1803.07268)

