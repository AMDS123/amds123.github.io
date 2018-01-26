---
layout: post
title: "Active Neural Localization"
date: 2018-01-24 22:06:55
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Devendra Singh Chaplot, Emilio Parisotto, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
Localization is the problem of estimating the location of an autonomous agent from an observation and a map of the environment. Traditional methods of localization, which filter the belief based on the observations, are sub-optimal in the number of steps required, as they do not decide the actions taken by the agent. We propose "Active Neural Localizer", a fully differentiable neural network that learns to localize accurately and efficiently. The proposed model incorporates ideas of traditional filtering-based localization methods, by using a structured belief of the state with multiplicative interactions to propagate belief, and combines it with a policy model to localize accurately while minimizing the number of steps required for localization. Active Neural Localizer is trained end-to-end with reinforcement learning. We use a variety of simulation environments for our experiments which include random 2D mazes, random mazes in the Doom game engine and a photo-realistic environment in the Unreal game engine. The results on the 2D environments show the effectiveness of the learned policy in an idealistic setting while results on the 3D environments demonstrate the model's capability of learning the policy and perceptual model jointly from raw-pixel based RGB observations. We also show that a model trained on random textures in the Doom environment generalizes well to a photo-realistic office space environment in the Unreal engine.

##### Abstract (translated by Google)
本地化是根据观测和环境地图来估计自主代理的位置的问题。传统的定位方法根据观察结果对信念进行过滤，在所需的步骤数量方面是次优的，因为它们并不决定代理所采取的行动。我们提出“主动神经定位器”，一个完全可微的神经网络，学习准确和有效的本地化。该模型结合了传统的基于过滤的定位方法的思想，通过使用具有乘法相互作用的状态的结构化信念来传播信念，并将其与策略模型结合以准确定位，同时最小化本地化所需的步骤数量。主动神经定位器通过强化学习进行端对端训练。我们在实验中使用了各种模拟环境，其中包括随机2D迷宫，Doom游戏引擎中的随机迷宫以及Unreal游戏引擎中的照片般逼真的环境。二维环境下的结果显示了理想化环境下学习策略的有效性，而三维环境下的结果显示了该模型从基于原始像素的RGB观测共同学习策略和感知模型的能力。我们还展示了在Doom环境中训练随机纹理的模型在虚幻引擎中相当逼真的办公空间环境。

##### URL
[http://arxiv.org/abs/1801.08214](http://arxiv.org/abs/1801.08214)

##### PDF
[http://arxiv.org/pdf/1801.08214](http://arxiv.org/pdf/1801.08214)

