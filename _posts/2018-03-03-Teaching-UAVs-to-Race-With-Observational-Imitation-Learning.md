---
layout: post
title: "Teaching UAVs to Race With Observational Imitation Learning"
date: 2018-03-03 09:17:42
categories: arXiv_CV
tags: arXiv_CV
author: Guohao Li, Matthias Mueller, Vincent Casser, Neil Smith, Dominik L. Michels, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has tackled the problem of autonomous navigation by imitating a teacher and learning an end-to-end policy, which directly predicts controls from raw images. However, these approaches tend to be sensitive to mistakes by the teacher and do not scale well to other environments or vehicles. To this end, we propose a modular network architecture that decouples perception from control, and is trained using Observational Imitation Learning (OIL), a novel imitation learning variant that supports online training and automatic selection of optimal behavior from observing multiple teachers. We apply our proposed methodology to the challenging problem of unmanned aerial vehicle (UAV) racing. We develop a simulator that enables the generation of large amounts of synthetic training data (both UAV captured images and its controls) and also allows for online learning and evaluation. We train a perception network to predict waypoints from raw image data and a control network to predict UAV controls from these waypoints using OIL. Our modular network is able to autonomously fly a UAV through challenging race tracks at high speeds. Extensive experiments demonstrate that our trained network outperforms its teachers, end-to-end baselines, and even human pilots in simulation. The supplementary video can be viewed at https://youtu.be/PeTXSoriflc

##### Abstract (translated by Google)
最近的工作通过模仿教师和学习端到端策略来解决自主导航问题，该策略直接预测来自原始图像的控制。然而，这些方法往往对老师的错误很敏感，并且不能很好地适应其他环境或车辆。为此，我们提出了一种将感知与控制分离的模块化网络架构，并且使用观察仿真学习（OIL）进行训练，该仿真学习变体支持在线培训并通过观察多位教师自动选择最佳行为。我们将我们提出的方法应用于无人驾驶飞行器（UAV）比赛的挑战性问题。我们开发了一个模拟器，可以生成大量的综合训练数据（包括无人机拍摄的图像及其控制），还可以进行在线学习和评估。我们训练一个感知网络，根据原始图像数据和控制网络预测航点，从而通过使用OIL从这些航点中预测无人机控制。我们的模块化网络能够通过高速挑战赛道自主驾驶无人机。大量实验表明，我们的训练网络在模拟方面优于老师，端到端基线甚至人类飞行员。补充视频可在https://youtu.be/PeTXSoriflc查看

##### URL
[http://arxiv.org/abs/1803.01129](http://arxiv.org/abs/1803.01129)

##### PDF
[http://arxiv.org/pdf/1803.01129](http://arxiv.org/pdf/1803.01129)

