---
layout: post
title: "Learning Dynamic Memory Networks for Object Tracking"
date: 2018-09-02 05:09:02
categories: arXiv_CV
tags: arXiv_CV Dynamic_Memory_Network Attention Tracking Object_Tracking RNN Detection Memory_Networks
author: Tianyu Yang, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Template-matching methods for visual tracking have gained popularity recently due to their comparable performance and fast speed. However, they lack effective ways to adapt to changes in the target object's appearance, making their tracking accuracy still far from state-of-the-art. In this paper, we propose a dynamic memory network to adapt the template to the target's appearance variations during tracking. An LSTM is used as a memory controller, where the input is the search feature map and the outputs are the control signals for the reading and writing process of the memory block. As the location of the target is at first unknown in the search feature map, an attention mechanism is applied to concentrate the LSTM input on the potential target. To prevent aggressive model adaptivity, we apply gated residual template learning to control the amount of retrieved memory that is used to combine with the initial template. Unlike tracking-by-detection methods where the object's information is maintained by the weight parameters of neural networks, which requires expensive online fine-tuning to be adaptable, our tracker runs completely feed-forward and adapts to the target's appearance changes by updating the external memory. Moreover, unlike other tracking methods where the model capacity is fixed after offline training --- the capacity of our tracker can be easily enlarged as the memory requirements of a task increase, which is favorable for memorizing long-term object information. Extensive experiments on OTB and VOT demonstrates that our tracker MemTrack performs favorably against state-of-the-art tracking methods while retaining real-time speed of 50 fps.

##### Abstract (translated by Google)
用于视觉跟踪的模板匹配方法由于其可比较的性能和快速速度而最近获得了普及。然而，它们缺乏适应目标物体外观变化的有效方法，使得它们的跟踪精度仍然远离最先进的技术。在本文中，我们提出了一个动态记忆网络，以使模板适应目标在跟踪过程中的外观变化。 LSTM用作存储器控制器，其中输入是搜索特征映射，输出是用于存储器块的读取和写入过程的控制信号。由于目标的位置在搜索特征图中首先是未知的，因此应用注意机制来将LSTM输入集中在潜在目标上。为了防止积极的模型适应性，我们应用门控残差模板学习来控制用于与初始模板组合的检索内存量。与通过神经网络的权重参数维护对象信息的跟踪检测方法不同，这需要昂贵的在线微调以适应，我们的跟踪器完全前馈并通过更新外部来适应目标的外观变化记忆。此外，与离线训练后模型容量固定的其他跟踪方法不同 - 随着任务的内存需求增加，我们的跟踪器的容量可以很容易地扩大，这有利于记忆长期对象信息。在OTB和VOT上进行的大量实验表明，我们的跟踪器MemTrack在保持50 fps的实时速度的同时，对最先进的跟踪方法表现出色。

##### URL
[http://arxiv.org/abs/1803.07268](http://arxiv.org/abs/1803.07268)

##### PDF
[http://arxiv.org/pdf/1803.07268](http://arxiv.org/pdf/1803.07268)

