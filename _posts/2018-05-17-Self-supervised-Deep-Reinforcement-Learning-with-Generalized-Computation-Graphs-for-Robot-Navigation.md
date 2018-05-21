---
layout: post
title: "Self-supervised Deep Reinforcement Learning with Generalized Computation Graphs for Robot Navigation"
date: 2018-05-17 22:32:25
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Gregory Kahn, Adam Villaflor, Bosen Ding, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Enabling robots to autonomously navigate complex environments is essential for real-world deployment. Prior methods approach this problem by having the robot maintain an internal map of the world, and then use a localization and planning method to navigate through the internal map. However, these approaches often include a variety of assumptions, are computationally intensive, and do not learn from failures. In contrast, learning-based methods improve as the robot acts in the environment, but are difficult to deploy in the real-world due to their high sample complexity. To address the need to learn complex policies with few samples, we propose a generalized computation graph that subsumes value-based model-free methods and model-based methods, with specific instantiations interpolating between model-free and model-based. We then instantiate this graph to form a navigation model that learns from raw images and is sample efficient. Our simulated car experiments explore the design decisions of our navigation model, and show our approach outperforms single-step and $N$-step double Q-learning. We also evaluate our approach on a real-world RC car and show it can learn to navigate through a complex indoor environment with a few hours of fully autonomous, self-supervised training. Videos of the experiments and code can be found at github.com/gkahn13/gcg

##### Abstract (translated by Google)
使机器人能够自主导航复杂的环境对于真实世界的部署至关重要。先前的方法通过让机器人保持世界的内部地图来解决这个问题，然后使用本地化和规划方法来浏览内部地图。然而，这些方法通常包括各种假设，计算密集型，并且不从失败中学习。相比之下，基于学习的方法随着机器人在环境中的行为而改善，但由于样本复杂性高，难以在现实世界中部署。为了解决用少量样本学习复杂策略的需求，我们提出了一个广义计算图，其中包含基于价值的无模型方法和基于模型的方法，其中具体实例在无模型模型和基于模型之间进行插值。然后，我们将这个图形实例化，形成一个从原始图像学习并且样本有效的导航模型。我们的模拟车实验探索了我们的导航模型的设计决策，并显示​​我们的方法优于单步和$ N $ -step双Q学习。我们还评估了我们在真实世界的遥控车上的方法，并展示了它可以学习如何在复杂的室内环境中驾驶几小时完全自主的自我监督训练。实验和代码的视频可以在github.com/gkahn13/gcg找到

##### URL
[http://arxiv.org/abs/1709.10489](http://arxiv.org/abs/1709.10489)

##### PDF
[http://arxiv.org/pdf/1709.10489](http://arxiv.org/pdf/1709.10489)

