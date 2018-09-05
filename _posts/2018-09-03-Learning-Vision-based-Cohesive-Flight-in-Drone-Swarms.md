---
layout: post
title: "Learning Vision-based Cohesive Flight in Drone Swarms"
date: 2018-09-03 10:44:28
categories: arXiv_CV
tags: arXiv_CV Salient Weakly_Supervised Drone CNN Detection
author: Fabian Schilling, Julien Lecoeur, Fabrizio Schiano, Dario Floreano
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a data-driven approach to learning vision-based collective behavior from a simple flocking algorithm. We simulate a swarm of quadrotor drones and formulate the controller as a regression problem in which we generate 3D velocity commands directly from raw camera images. The dataset is created by simultaneously acquiring omnidirectional images and computing the corresponding control command from the flocking algorithm. We show that a convolutional neural network trained on the visual inputs of the drone can learn not only robust collision avoidance but also coherence of the flock in a sample-efficient manner. The neural controller effectively learns to localize other agents in the visual input, which we show by visualizing the regions with the most influence on the motion of an agent. This weakly supervised saliency map can be computed efficiently and may be used as a prior for subsequent detection and relative localization of other agents. We remove the dependence on sharing positions among flock members by taking only local visual information into account for control. Our work can therefore be seen as the first step towards a fully decentralized, vision-based flock without the need for communication or visual markers to aid detection of other agents.

##### Abstract (translated by Google)
本文介绍了一种基于数据驱动的方法，通过简单的植绒算法来学习基于视觉的集体行为。我们模拟一群四旋翼无人机并将控制器公式化为回归问题，我们直接从原始相机图像生成3D速度命令。通过同时获取全向图像并从植绒算法计算相应的控制命令来创建数据集。我们表明，在无人机的视觉输入上训练的卷积神经网络不仅可以学习有效的方式，还可以学习强大的碰撞避免以及鸡群的相干性。神经控制器有效地学习在视觉输入中定位其他代理，我们通过可视化对代理运动影响最大的区域来显示。可以有效地计算该弱监督显着图，并且可以将其用作先前用于其他代理的后续检测和相对定位。我们通过仅考虑本地视觉信息来消除对群体成员之间共享位置的依赖性。因此，我们的工作可以被视为迈向完全分散的，基于视觉的鸡群的第一步，而无需通信或视觉标记来帮助检测其他药剂。

##### URL
[http://arxiv.org/abs/1809.00543](http://arxiv.org/abs/1809.00543)

##### PDF
[http://arxiv.org/pdf/1809.00543](http://arxiv.org/pdf/1809.00543)

