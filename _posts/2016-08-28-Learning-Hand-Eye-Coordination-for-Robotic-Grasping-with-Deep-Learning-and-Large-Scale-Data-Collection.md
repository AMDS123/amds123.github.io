---
layout: post
title: "Learning Hand-Eye Coordination for Robotic Grasping with Deep Learning and Large-Scale Data Collection"
date: 2016-08-28 23:32:37
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation
author: Sergey Levine, Peter Pastor, Alex Krizhevsky, Deirdre Quillen
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a learning-based approach to hand-eye coordination for robotic grasping from monocular images. To learn hand-eye coordination for grasping, we trained a large convolutional neural network to predict the probability that task-space motion of the gripper will result in successful grasps, using only monocular camera images and independently of camera calibration or the current robot pose. This requires the network to observe the spatial relationship between the gripper and objects in the scene, thus learning hand-eye coordination. We then use this network to servo the gripper in real time to achieve successful grasps. To train our network, we collected over 800,000 grasp attempts over the course of two months, using between 6 and 14 robotic manipulators at any given time, with differences in camera placement and hardware. Our experimental evaluation demonstrates that our method achieves effective real-time control, can successfully grasp novel objects, and corrects mistakes by continuous servoing.

##### Abstract (translated by Google)
我们描述了一种基于学习的手势协调机器人从单眼图像抓握的方法。为了掌握手眼协调，我们训练了一个大卷积神经网络来预测抓手的任务空间运动将导致成功抓握的概率，只使用单目摄像机图像，而不依赖于摄像机标定或当前的机器人姿态。这就要求网络观察抓手与场景中物体的空间关系，从而学习手眼协调。然后，我们使用这个网络实时伺服抓手，实现成功的抓握。为了训练我们的网络，我们在两个月的时间里收集了超过800,000次的抓握尝试，在任何给定时间使用6到14个机器人操纵器，并且在摄像机位置和硬件方面有所不同。我们的实验评估表明，我们的方法实现了有效的实时控制，可以成功地抓住新的对象，并通过连续伺服纠正错误。

##### URL
[https://arxiv.org/abs/1603.02199](https://arxiv.org/abs/1603.02199)

##### PDF
[https://arxiv.org/pdf/1603.02199](https://arxiv.org/pdf/1603.02199)

