---
layout: post
title: "DeepDriving: Learning Affordance for Direct Perception in Autonomous Driving"
date: 2015-09-26 05:17:59
categories: arXiv_CV
tags: arXiv_CV CNN
author: Chenyi Chen, Ari Seff, Alain Kornhauser, Jianxiong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
Today, there are two major paradigms for vision-based autonomous driving systems: mediated perception approaches that parse an entire scene to make a driving decision, and behavior reflex approaches that directly map an input image to a driving action by a regressor. In this paper, we propose a third paradigm: a direct perception approach to estimate the affordance for driving. We propose to map an input image to a small number of key perception indicators that directly relate to the affordance of a road/traffic state for driving. Our representation provides a set of compact yet complete descriptions of the scene to enable a simple controller to drive autonomously. Falling in between the two extremes of mediated perception and behavior reflex, we argue that our direct perception representation provides the right level of abstraction. To demonstrate this, we train a deep Convolutional Neural Network using recording from 12 hours of human driving in a video game and show that our model can work well to drive a car in a very diverse set of virtual environments. We also train a model for car distance estimation on the KITTI dataset. Results show that our direct perception approach can generalize well to real driving images. Source code and data are available on our project website.

##### Abstract (translated by Google)
目前，基于视觉的自主驾驶系统主要有两种模式：解析整个场景以进行驾驶决策的中介感知方法，以及通过回归器直接将输入图像映射到驾驶行为的行为反射方法。在本文中，我们提出了第三种模式：直接感知方法来估计驾驶的可行性。我们建议将输入图像映射到少数与驾驶的道路/交通状态的可供性直接相关的关键感知指标。我们的代表提供了一套紧凑而完整的场景描述，使简单的控制器能够自主驾驶。落在中介感知和行为反射的两个极端之间，我们认为我们的直接感知表示提供了正确的抽象水平。为了证明这一点，我们使用视频游戏中的12小时驾驶记录来训练深度卷积神经网络，并显示我们的模型可以很好地在非常多元化的虚拟环境中驾驶汽车。我们还训练KITTI数据集上的车辆距离估计模型。结果表明，我们的直接感知方法可以很好地推广到真实的驾驶图像。源代码和数据可在我们的项目网站上找到。

##### URL
[https://arxiv.org/abs/1505.00256](https://arxiv.org/abs/1505.00256)

##### PDF
[https://arxiv.org/pdf/1505.00256](https://arxiv.org/pdf/1505.00256)

