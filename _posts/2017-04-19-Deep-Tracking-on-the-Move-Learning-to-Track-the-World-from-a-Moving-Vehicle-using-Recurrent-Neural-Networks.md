---
layout: post
title: "Deep Tracking on the Move: Learning to Track the World from a Moving Vehicle using Recurrent Neural Networks"
date: 2017-04-19 14:31:32
categories: arXiv_CV
tags: arXiv_CV Tracking RNN
author: Julie Dequaire, Dushyant Rao, Peter Ondruska, Dominic Wang, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an end-to-end approach for tracking static and dynamic objects for an autonomous vehicle driving through crowded urban environments. Unlike traditional approaches to tracking, this method is learned end-to-end, and is able to directly predict a full unoccluded occupancy grid map from raw laser input data. Inspired by the recently presented DeepTracking approach [Ondruska, 2016], we employ a recurrent neural network (RNN) to capture the temporal evolution of the state of the environment, and propose to use Spatial Transformer modules to exploit estimates of the egomotion of the vehicle. Our results demonstrate the ability to track a range of objects, including cars, buses, pedestrians, and cyclists through occlusion, from both moving and stationary platforms, using a single learned model. Experimental results demonstrate that the model can also predict the future states of objects from current inputs, with greater accuracy than previous work.

##### Abstract (translated by Google)
本文提出了一个端到端的方法来跟踪在拥挤的城市环境中驾驶的自主车辆的静态和动态物体。与传统的跟踪方法不同，这种方法是端到端学习的，可以直接从原始激光输入数据预测完全未被遮挡的占用网格图。受最近提出的DeepTracking方法的启发[Ondruska，2016]，我们采用递归神经网络（RNN）来捕捉环境状态的时间演变，并建议使用空间变换器模块来估计车辆的运动。我们的研究结果表明，使用单一的学习模型，可以从移动平台和固定平台通过遮挡来跟踪一系列物体，包括汽车，公交车，行人和骑自行车者。实验结果表明，该模型还可以预测当前输入对象的未来状态，比以前的工作具有更高的准确性。

##### URL
[https://arxiv.org/abs/1609.09365](https://arxiv.org/abs/1609.09365)

##### PDF
[https://arxiv.org/pdf/1609.09365](https://arxiv.org/pdf/1609.09365)

