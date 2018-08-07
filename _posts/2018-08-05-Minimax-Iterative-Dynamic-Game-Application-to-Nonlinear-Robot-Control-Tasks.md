---
layout: post
title: "Minimax Iterative Dynamic Game: Application to Nonlinear Robot Control Tasks"
date: 2018-08-05 06:04:45
categories: arXiv_RO
tags: arXiv_RO Adversarial
author: Olalekan Ogunmolu, Nicholas Gans, Tyler Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Multistage decision policies provide useful control strategies in high-dimensional state spaces, particularly in complex control tasks. However, they exhibit weak performance guarantees in the presence of disturbance, model mismatch, or model uncertainties. This brittleness limits their use in high-risk scenarios. We present how to quantify the sensitivity of such policies in order to inform of their robustness capacity. We also propose a minimax iterative dynamic game framework for designing robust policies in the presence of disturbance/uncertainties. We test the quantification hypothesis on a carefully designed deep neural network policy; we then pose a minimax iterative dynamic game (iDG) framework for improving policy robustness in the presence of adversarial disturbances. We evaluate our iDG framework on a mecanum-wheeled robot, whose goal is to find a ocally robust optimal multistage policy that achieve a given goal-reaching task. The algorithm is simple and adaptable for designing meta-learning/deep policies that are robust against disturbances, model mismatch, or model uncertainties, up to a disturbance bound. Videos of the results are on the author's website, <a href="http://ecs.utdallas.edu/~opo140030/iros18/iros2018.html">this http URL</a>, while the codes for reproducing our experiments are on github, https://github.com/lakehanne/youbot/tree/rilqg. A self-contained environment for reproducing our results is on docker, https://hub.docker.com/r/lakehanne/youbotbuntu14/

##### Abstract (translated by Google)
多级决策策略在高维状态空间中提供有用的控制策略，特别是在复杂的控制任务中。然而，在存在干扰，模型不匹配或模型不确定性的情况下，它们表现出弱的性能保证。这种脆弱性限制了它们在高风险情况下的使用。我们将介绍如何量化这些政策的敏感性，以便了解其稳健性能力。我们还提出了一个minimax迭代动态游戏框架，用于在存在干扰/不确定性的情况下设计稳健的策略。我们在精心设计的深度神经网络策略上测试量化假设;然后，我们构建一个minimax迭代动态游戏（iDG）框架，用于在存在对抗性干扰的情况下改善策略稳健性。我们在mecanum轮式机器人上评估我们的iDG框架，其目标是找到一个实现特定目标任务的最佳多阶段策略。该算法简单且适用于设计元学习/深度策略，该策略对干扰，模型不匹配或模型不确定性具有鲁棒性，直至干扰限制。结果视频在作者的网站上，<a href="http://ecs.utdallas.edu/~opo140030/iros18/iros2018.html">此http网址</a>，同时用于复制我们实验的代码在github上，https：//github.com/lakehanne/youbot/tree/rilqg。用于复制我们结果的独立环境在docker上，https：//hub.docker.com/r/lakehanne/youbotbuntu14/

##### URL
[http://arxiv.org/abs/1710.00491](http://arxiv.org/abs/1710.00491)

##### PDF
[http://arxiv.org/pdf/1710.00491](http://arxiv.org/pdf/1710.00491)

