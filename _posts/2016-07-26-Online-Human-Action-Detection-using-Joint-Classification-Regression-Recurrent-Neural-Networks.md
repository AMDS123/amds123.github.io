---
layout: post
title: "Online Human Action Detection using Joint Classification-Regression Recurrent Neural Networks"
date: 2016-07-26 15:54:07
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition Optimization RNN Classification Detection Recognition
author: Yanghao Li, Cuiling Lan, Junliang Xing, Wenjun Zeng, Chunfeng Yuan, Jiaying Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Human action recognition from well-segmented 3D skeleton data has been intensively studied and has been attracting an increasing attention. Online action detection goes one step further and is more challenging, which identifies the action type and localizes the action positions on the fly from the untrimmed stream data. In this paper, we study the problem of online action detection from streaming skeleton data. We propose a multi-task end-to-end Joint Classification-Regression Recurrent Neural Network to better explore the action type and temporal localization information. By employing a joint classification and regression optimization objective, this network is capable of automatically localizing the start and end points of actions more accurately. Specifically, by leveraging the merits of the deep Long Short-Term Memory (LSTM) subnetwork, the proposed model automatically captures the complex long-range temporal dynamics, which naturally avoids the typical sliding window design and thus ensures high computational efficiency. Furthermore, the subtask of regression optimization provides the ability to forecast the action prior to its occurrence. To evaluate our proposed model, we build a large streaming video dataset with annotations. Experimental results on our dataset and the public G3D dataset both demonstrate very promising performance of our scheme.

##### Abstract (translated by Google)
人们对精细分割的三维骨骼数据的人体动作识别已经得到了深入的研究，并引起越来越多的关注。在线行动检测更进一步，更具挑战性，它识别行动类型并根据未修改的流数据即时定位行动位置。在本文中，我们研究了流式骨架数据在线动作检测的问题。我们提出了一个多任务端到端联合分类回归递归神经网络来更好地探索动作类型和时间定位信息。通过采用联合分类和回归优化目标，该网络能够更准确地自动定位动作的起点和终点。具体而言，通过利用深度长时间记忆（LSTM）子网络的优点，所提出的模型自动捕获复杂的远程时间动态，这自然避免了典型的滑动窗口设计，从而确保了高计算效率。此外，回归优化的子任务提供了预测动作发生之前的能力。为了评估我们提出的模型，我们建立了一个包含注释的大型流视频数据集。我们的数据集和公共G3D数据集的实验结果都表明了我们的方案的非常有前途的性能。

##### URL
[https://arxiv.org/abs/1604.05633](https://arxiv.org/abs/1604.05633)

##### PDF
[https://arxiv.org/pdf/1604.05633](https://arxiv.org/pdf/1604.05633)

