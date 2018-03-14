---
layout: post
title: "Using Parameterized Black-Box Priors to Scale Up Model-Based Policy Search for Robotics"
date: 2018-03-13 16:39:40
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Konstantinos Chatzilygeroudis, Jean-Baptiste Mouret
mathjax: true
---

* content
{:toc}

##### Abstract
The most data-efficient algorithms for reinforcement learning in robotics are model-based policy search algorithms, which alternate between learning a dynamical model of the robot and optimizing a policy to maximize the expected return given the model and its uncertainties. Among the few proposed approaches, the recently introduced Black-DROPS algorithm exploits a black-box optimization algorithm to achieve both high data-efficiency and good computation times when several cores are used; nevertheless, like all model-based policy search approaches, Black-DROPS does not scale to high dimensional state/action spaces. In this paper, we introduce a new model learning procedure in Black-DROPS that leverages parameterized black-box priors to (1) scale up to high-dimensional systems, and (2) be robust to large inaccuracies of the prior information. We demonstrate the effectiveness of our approach with the "pendubot" swing-up task in simulation and with a physical hexapod robot (48D state space, 18D action space) that has to walk forward as fast as possible. The results show that our new algorithm is more data-efficient than previous model-based policy search algorithms (with and without priors) and that it can allow a physical 6-legged robot to learn new gaits in only 16 to 30 seconds of interaction time.

##### Abstract (translated by Google)
用于机器人强化学习的最具数据效率的算法是基于模型的策略搜索算法，该算法在学习机器人的动力学模型和优化策略之间交替，从而在给定模型及其不确定性的情况下最大化策略。在少数提出的方法中，最近推出的Black-DROPS算法采用黑盒优化算法，以在使用多个核时实现高数据效率和良好的计算时间;尽管如此，像所有基于模型的策略搜索方法一样，Black-DROPS不能扩展到高维状态/动作空间。在本文中，我们在Black-DROPS中引入了一种新的模型学习过程，该过程利用参数化的黑盒子先验来（1）扩展到高维系统，以及（2）对先验信息的大量不准确性具有鲁棒性。我们展示了我们的方法在仿真中使用“pendubot”摆动任务以及必须尽快前进的物理六足机器人（48D状态空间，18D动作空间）的有效性。结果表明，我们的新算法比以前的基于模型的策略搜索算法（有和没有先验）更具数据效率，并且它可以允许一个物理的6腿机器人在仅16到30秒的交互时间内学习新的步态。

##### URL
[http://arxiv.org/abs/1709.06917](http://arxiv.org/abs/1709.06917)

##### PDF
[http://arxiv.org/pdf/1709.06917](http://arxiv.org/pdf/1709.06917)

