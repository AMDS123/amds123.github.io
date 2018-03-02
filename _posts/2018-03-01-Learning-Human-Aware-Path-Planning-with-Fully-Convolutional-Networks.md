---
layout: post
title: "Learning Human-Aware Path Planning with Fully Convolutional Networks"
date: 2018-03-01 15:08:14
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning CNN Classification Prediction
author: No&#xe9; P&#xe9;rez-Higueras, Fernando Caballero, Luis Merino
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents an approach to learn path planning for robot social navigation by demonstration. We make use of Fully Convolutional Neural Networks (FCNs) to learn from expert's path demonstrations a map that marks a feasible path to the goal as a classification problem. The use of FCNs allows us to overcome the problem of manually designing/identifying the cost-map and relevant features for the task of robot navigation. The method makes use of optimal Rapidly-exploring Random Tree planner (RRT*) to overcome eventual errors in the path prediction; the FCNs prediction is used as cost-map and also to partially bias the sampling of the configuration space, leading the planner to behave similarly to the learned expert behavior. The approach is evaluated in experiments with real trajectories and compared with Inverse Reinforcement Learning algorithms that use RRT* as underlying planner.

##### Abstract (translated by Google)
这项工作提出了一种通过示范学习机器人社交导航路径规划的方法。我们利用完全卷积神经网络（FCNs）从专家的路径示例中学习一张地图，该地图将划分为目标的可行路径作为分类问题。 FCN的使用使我们能够克服手动设计/识别机器人导航任务的成本地图和相关特征的问题。该方法利用最优的快速探索随机树规划器（RRT *）来克服路径预测中的最终误差; FCNs预测被用作成本映射，并且还部分地偏向配置空间的采样，从而使得计划者的行为与所学习到的专家行为类似。该方法在具有真实轨迹的实验中进行评估，并与使用RRT *作为基本规划器的反向增强学习算法进行比较。

##### URL
[http://arxiv.org/abs/1803.00429](http://arxiv.org/abs/1803.00429)

##### PDF
[http://arxiv.org/pdf/1803.00429](http://arxiv.org/pdf/1803.00429)

