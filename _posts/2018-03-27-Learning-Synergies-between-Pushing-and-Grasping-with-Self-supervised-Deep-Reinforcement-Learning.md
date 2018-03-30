---
layout: post
title: "Learning Synergies between Pushing and Grasping with Self-supervised Deep Reinforcement Learning"
date: 2018-03-27 08:31:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning CNN
author: Andy Zeng, Shuran Song, Stefan Welker, Johnny Lee, Alberto Rodriguez, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
Skilled robotic manipulation benefits from complex synergies between non-prehensile (e.g. pushing) and prehensile (e.g. grasping) actions: pushing can help rearrange cluttered objects to make space for arms and fingers; likewise, grasping can help displace objects to make pushing movements more precise and collision-free. In this work, we demonstrate that it is possible to discover and learn these synergies from scratch through model-free deep reinforcement learning. Our method involves training two fully convolutional networks that map from visual observations to actions: one infers the utility of pushes for a dense pixel-wise sampling of end effector orientations and locations, while the other does the same for grasping. Both networks are trained jointly in a Q-learning framework and are entirely self-supervised by trial and error, where rewards are provided from successful grasps. In this way, our policy learns pushing motions that enable future grasps, while learning grasps that can leverage past pushes. During picking experiments in both simulation and real-world scenarios, we find that our system quickly learns complex behaviors amid challenging cases of clutter, and achieves better grasping success rates and picking efficiencies than baseline alternatives after only a few hours of training. We further demonstrate that our method is capable of generalizing to novel objects. Qualitative results (videos), code, pre-trained models, and simulation environments are available at this http URL

##### Abstract (translated by Google)
熟练的机器人操纵受益于非吸收性（例如推动）和吸收（例如抓握）动作之间复杂的协同作用：推动可帮助重新排列杂乱的物体以为手臂和手指腾出空间;同样，抓握可以帮助移动物体，使推动运动更加精确和无碰撞。在这项工作中，我们证明可以通过无模型深层强化学习从头开始发现和学习这些协同作用。我们的方法涉及训练两个完全卷积网络，从视觉观察到动作映射：推断推动效用器的端点效应器方向和位置的密集像素采样的效用，而另一个则用于抓取。这两个网络都是在Q-learning框架中共同训练的，并且完全由反复试验来自我监督，奖励来自成功的抓握。通过这种方式，我们的政策学习推动运动，使未来的抓住，同时学习掌握可以利用过去的推动。在模拟和现实世界的情景下进行采摘实验期间，我们发现我们的系统能够在具有挑战性的杂乱情况下快速学习复杂的行为，并且在仅仅几个小时的培训后就能比基线方案更好地掌握成功率和提取效率。我们进一步证明我们的方法能够推广到新颖的对象。此http URL提供定性结果（视频），代码，预先训练的模型和模拟环境

##### URL
[https://arxiv.org/abs/1803.09956](https://arxiv.org/abs/1803.09956)

##### PDF
[https://arxiv.org/pdf/1803.09956](https://arxiv.org/pdf/1803.09956)

