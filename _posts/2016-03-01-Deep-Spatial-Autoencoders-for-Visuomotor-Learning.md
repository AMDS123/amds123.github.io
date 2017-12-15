---
layout: post
title: "Deep Spatial Autoencoders for Visuomotor Learning"
date: 2016-03-01 17:24:50
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Chelsea Finn, Xin Yu Tan, Yan Duan, Trevor Darrell, Sergey Levine, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning provides a powerful and flexible framework for automated acquisition of robotic motion skills. However, applying reinforcement learning requires a sufficiently detailed representation of the state, including the configuration of task-relevant objects. We present an approach that automates state-space construction by learning a state representation directly from camera images. Our method uses a deep spatial autoencoder to acquire a set of feature points that describe the environment for the current task, such as the positions of objects, and then learns a motion skill with these feature points using an efficient reinforcement learning method based on local linear models. The resulting controller reacts continuously to the learned feature points, allowing the robot to dynamically manipulate objects in the world with closed-loop control. We demonstrate our method with a PR2 robot on tasks that include pushing a free-standing toy block, picking up a bag of rice using a spatula, and hanging a loop of rope on a hook at various positions. In each task, our method automatically learns to track task-relevant objects and manipulate their configuration with the robot's arm.

##### Abstract (translated by Google)
强化学习为机器人动作技能的自动获取提供了强大且灵活的框架。但是，应用强化学习需要对状态进行充分详细的表示，包括任务相关对象的配置。我们提出一种通过直接从相机图像中学习状态表示来自动化状态空间构建的方法。我们的方法使用深度空间自动编码器来获取描述当前任务的环境（例如对象的位置）的一组特征点，然后使用基于局部线性的有效强化学习方法学习具有这些特征点的运动技能楷模。由此产生的控制器不断反应学习的特征点，使机器人能够通过闭环控制动态地操纵世界上的物体。我们用一台PR2机器人演示了我们的方法，包括推动一个独立的玩具块，用铲子拿起一袋大米，并在各种位置的吊钩上挂一圈绳子。在每个任务中，我们的方法会自动学习跟踪与任务相关的对象，并使用机器人的手臂操作它们的配置。

##### URL
[https://arxiv.org/abs/1509.06113](https://arxiv.org/abs/1509.06113)

##### PDF
[https://arxiv.org/pdf/1509.06113](https://arxiv.org/pdf/1509.06113)

