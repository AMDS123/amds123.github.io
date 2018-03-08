---
layout: post
title: "Discontinuity-Sensitive Optimal Control Learning by Mixture of Experts"
date: 2018-03-07 01:21:57
categories: arXiv_RO
tags: arXiv_RO Tracking Reinforcement_Learning Prediction
author: Gao Tang, Kris Hauser
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a discontinuity-sensitive approach to learn the solutions of parametric optimal control problems with high accuracy. Many tasks, ranging from model predictive control to reinforcement learning, may be solved by learning optimal solutions as a function of problem parameters. However, nonconvexity, discrete homotopy classes, and control switching cause discontinuity in the parameter-solution mapping, thus making learning difficult for traditional continuous function approximators. A mixture of experts (MoE) model composed of a classifier and several regressors is proposed to address such an issue. The optimal trajectories of different parameters are clustered such that in each cluster the trajectories are continuous function of problem parameters. Numerical examples on benchmark problems show that training the classifier and regressors individually outperforms joint training of MoE. With suitably chosen clusters, this approach not only achieves lower prediction error with less training data and fewer model parameters, but also leads to dramatic improvements in the reliability of trajectory tracking compared to traditional universal function approximation models (e.g., neural networks).

##### Abstract (translated by Google)
本文提出了一种非连续性敏感的方法来高精度地学习参数最优控制问题的解决方案。许多任务，从模型预测控制到强化学习，都可以通过学习最优解作为问题参数的函数来解决。然而，非凸性，离散同伦类和控制切换会引起参数 - 解映射的不连续性，从而导致传统连续函数逼近器的学习变得困难。为解决这个问题，提出了由分类器和多个回归器组成的专家模型（MoE）模型。不同参数的最优轨迹被聚类，使得在每个群集中轨迹是问题参数的连续函数。基准问题的数值例子表明，训练分类器和回归器个别地胜过教育部的联合培训。通过适当选择的群集，该方法不仅可以用较少的训练数据和较少的模型参数实现较低的预测误差，而且与传统的通用函数逼近模型（例如神经网络）相比，还可以显着提高轨迹跟踪的可靠性。

##### URL
[http://arxiv.org/abs/1803.02493](http://arxiv.org/abs/1803.02493)

##### PDF
[http://arxiv.org/pdf/1803.02493](http://arxiv.org/pdf/1803.02493)

