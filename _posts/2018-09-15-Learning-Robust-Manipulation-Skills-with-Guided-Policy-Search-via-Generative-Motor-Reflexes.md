---
layout: post
title: "Learning Robust Manipulation Skills with Guided Policy Search via Generative Motor Reflexes"
date: 2018-09-15 13:24:17
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Philipp Ennen, Pia Bresenitz, Rene Vossen, Frank Hees
mathjax: true
---

* content
{:toc}

##### Abstract
Guided Policy Search enables robots to learn control policies for complex manipulation tasks efficiently. Therein, the control policies are represented as high-dimensional neural networks which derive robot actions based on states. However, due to the small number of real-world trajectory samples in Guided Policy Search, the resulting neural networks are only robust in the neighbourhood of the trajectory distribution explored by real-world interactions. In this paper, we present a new policy representation called Generative Motor Reflexes, which is able to generate robust actions over a broader state space compared to previous methods. In contrast to prior stateaction policies, Generative Motor Reflexes map states to parameters for a state-dependent motor reflex, which is then used to derive actions. Robustness is achieved by generating similar motor reflexes for arbitrary states. We evaluate the presented method in simulated and real-world manipulation tasks, including contact-rich peg-in-hole tasks. Using this evaluation tasks, we show that policies represented as Generative Motor Reflexes lead to robust manipulation skills also outside the explored trajectory distribution with less training needs compared to previous methods. Therefore, the presented approach serves as a step towards reliable applications of reinforcement learning for manipulation.

##### Abstract (translated by Google)
引导式策略搜索使机器人能够有效地学习复杂操作任务的控制策略。其中，控制策略表示为高维神经网络，其基于状态导出机器人动作。然而，由于引导策略搜索中的实际轨迹样本数量很少，所得到的神经网络仅在通过现实世界交互探索的轨迹分布附近是稳健的。在本文中，我们提出了一种名为Generative Motor Reflexes的新策略表示，与以前的方法相比，它能够在更广泛的状态空间上生成强大的动作。与先前的状态动作策略相反，Generative Motor Reflexes将状态映射到状态相关的运动反射的参数，然后用于推导动作。通过为任意状态产生类似的运动反射来实现稳健性。我们在模拟和实际操作任务中评估所提出的方法，包括接触丰富的桩孔任务。使用此评估任务，我们表明，与先前的方法相比，表示为生成性运动反射的策略在探索的轨迹分布之外导致强大的操作技能，并且训练需求较少。因此，所提出的方法用作朝向强化学习的可靠应用的步骤。

##### URL
[http://arxiv.org/abs/1809.05714](http://arxiv.org/abs/1809.05714)

##### PDF
[http://arxiv.org/pdf/1809.05714](http://arxiv.org/pdf/1809.05714)

