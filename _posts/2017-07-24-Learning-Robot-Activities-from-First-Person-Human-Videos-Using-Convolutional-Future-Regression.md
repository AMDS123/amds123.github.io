---
layout: post
title: "Learning Robot Activities from First-Person Human Videos Using Convolutional Future Regression"
date: 2017-07-24 08:02:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Prediction Detection
author: Jangwon Lee, Michael S. Ryoo
mathjax: true
---

* content
{:toc}

##### Abstract
We design a new approach that allows robot learning of new activities from unlabeled human example videos. Given videos of humans executing the same activity from a human's viewpoint (i.e., first-person videos), our objective is to make the robot learn the temporal structure of the activity as its future regression network, and learn to transfer such model for its own motor execution. We present a new deep learning model: We extend the state-of-the-art convolutional object detection network for the representation/estimation of human hands in training videos, and newly introduce the concept of using a fully convolutional network to regress (i.e., predict) the intermediate scene representation corresponding to the future frame (e.g., 1-2 seconds later). Combining these allows direct prediction of future locations of human hands and objects, which enables the robot to infer the motor control plan using our manipulation network. We experimentally confirm that our approach makes learning of robot activities from unlabeled human interaction videos possible, and demonstrate that our robot is able to execute the learned collaborative activities in real-time directly based on its camera input.

##### Abstract (translated by Google)
我们设计了一种新的方法，允许机器人从未标记的人体视频示例中学习新的活动。给定从人类视角执行相同活动的视频（即第一人称视频），我们的目标是让机器人学习活动的时间结构作为其未来的回归网络，并学习将这种模型转换为自己的模型电机执行。我们提出了一个新的深度学习模型：我们扩展了最先进的卷积物体检测网络，用于训练视频中人手的表示/估计，并且新引入使用完全卷积网络回归的概念（即，预测）与未来帧相对应的中间场景表示（例如1-2秒后）。结合这些可以直接预测未来人类手和物体的位置，从而使机器人能够使用我们的操作网络来推断电机控制计划。我们通过实验证实，我们的方法使得可以从无标签的人机交互视频学习机器人活动，并且证明我们的机器人能够基于其相机输入实时地直接执行学习的协作活动。

##### URL
[https://arxiv.org/abs/1703.01040](https://arxiv.org/abs/1703.01040)

##### PDF
[https://arxiv.org/pdf/1703.01040](https://arxiv.org/pdf/1703.01040)

