---
layout: post
title: "QT-Opt: Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation"
date: 2018-06-27 04:34:30
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Dmitry Kalashnikov, Alex Irpan, Peter Pastor, Julian Ibarz, Alexander Herzog, Eric Jang, Deirdre Quillen, Ethan Holly, Mrinal Kalakrishnan, Vincent Vanhoucke, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of learning vision-based dynamic manipulation skills using a scalable reinforcement learning approach. We study this problem in the context of grasping, a longstanding challenge in robotic manipulation. In contrast to static learning behaviors that choose a grasp point and then execute the desired grasp, our method enables closed-loop vision-based control, whereby the robot continuously updates its grasp strategy based on the most recent observations to optimize long-horizon grasp success. To that end, we introduce QT-Opt, a scalable self-supervised vision-based reinforcement learning framework that can leverage over 580k real-world grasp attempts to train a deep neural network Q-function with over 1.2M parameters to perform closed-loop, real-world grasping that generalizes to 96% grasp success on unseen objects. Aside from attaining a very high success rate, our method exhibits behaviors that are quite distinct from more standard grasping systems: using only RGB vision-based perception from an over-the-shoulder camera, our method automatically learns regrasping strategies, probes objects to find the most effective grasps, learns to reposition objects and perform other non-prehensile pre-grasp manipulations, and responds dynamically to disturbances and perturbations.

##### Abstract (translated by Google)
在本文中，我们使用可扩展的强化学习方法来研究学习基于视觉的动态操作技能的问题。我们在抓住这个机器人操纵的长期挑战的背景下研究这个问题。与选择抓点然后执行所需抓握的静态学习行为相比，我们的方法实现闭环视觉控制，机器人根据最近的观察结果不断更新其抓握策略，以优化长时间抓取成功。为此，我们引入了QT-Opt，这是一种可扩展的自我监督的基于视觉的强化学习框架，可以利用超过580k的真实世界抓取尝试来训练具有超过1.2M参数的深度神经网络Q函数，以执行闭环，真实世界的把握使96％的人认识到看不见的东西的成功。除了获得非常高的成功率之外，我们的方法表现出与更多标准抓取系统截然不同的行为：我们的方法仅使用基于RGB视觉的感知，可以自动学习重新配准策略，探测要查找的对象最有效的抓握，学习重新定位对象并执行其他非易懂的预抓握操作，并动态响应干扰和扰动。

##### URL
[http://arxiv.org/abs/1806.10293](http://arxiv.org/abs/1806.10293)

##### PDF
[http://arxiv.org/pdf/1806.10293](http://arxiv.org/pdf/1806.10293)

