---
layout: post
title: "Imitation from Observation: Learning to Imitate Behaviors from Raw Video via Context Translation"
date: 2018-06-18 21:00:13
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: YuXuan Liu, Abhishek Gupta, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Imitation learning is an effective approach for autonomous systems to acquire control policies when an explicit reward function is unavailable, using supervision provided as demonstrations from an expert, typically a human operator. However, standard imitation learning methods assume that the agent receives examples of observation-action tuples that could be provided, for instance, to a supervised learning algorithm. This stands in contrast to how humans and animals imitate: we observe another person performing some behavior and then figure out which actions will realize that behavior, compensating for changes in viewpoint, surroundings, object positions and types, and other factors. We term this kind of imitation learning "imitation-from-observation," and propose an imitation learning method based on video prediction with context translation and deep reinforcement learning. This lifts the assumption in imitation learning that the demonstration should consist of observations in the same environment configuration, and enables a variety of interesting applications, including learning robotic skills that involve tool use simply by observing videos of human tool use. Our experimental results show the effectiveness of our approach in learning a wide range of real-world robotic tasks modeled after common household chores from videos of a human demonstrator, including sweeping, ladling almonds, pushing objects as well as a number of tasks in simulation.

##### Abstract (translated by Google)
模仿学习是自主系统获得控制策略时的一种有效方法，当明确的奖励功能不可用时，使用专家（通常是人类操作员）的演示提供监督。然而，标准模仿学习方法假定代理接收可以提供的观察动作元组的例子，例如，监督学习算法。这与人类和动物模仿的方式不同：我们观察另一个人执行某种行为，然后找出哪些行为会实现该行为，补偿视点，周围环境，对象位置和类型以及其他因素的变化。我们称这种模仿学习为“从观察中模仿”，并提出了一种基于视频预测的模仿学习方法，具有上下文翻译和深层强化学习。这提升了模仿学习中的假设，即演示应该包括在相同环境配置下的观察，并且可以实现各种有趣的应用，包括仅通过观察人工工具使用的视频来学习涉及工具使用的机器人技能。我们的实验结果显示了我们的方法在学习大量真实世界中的机器人任务方面的有效性，这些任务是从人类演示视频的共同家务中完成的，其中包括清扫，搅拌杏仁，推动物体以及仿真中的许多任务。

##### URL
[http://arxiv.org/abs/1707.03374](http://arxiv.org/abs/1707.03374)

##### PDF
[http://arxiv.org/pdf/1707.03374](http://arxiv.org/pdf/1707.03374)

