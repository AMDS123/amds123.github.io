---
layout: post
title: "Learning Sample-Efficient Target Reaching for Mobile Robots"
date: 2018-03-05 03:45:53
categories: arXiv_RO
tags: arXiv_RO Sparse CNN
author: Arbaaz Khan, Vijay Kumar, Alejandro Ribeiro
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel architecture and a self-supervised policy gradient algorithm, which employs unsupervised auxiliary tasks to enable a mobile robot to learn how to navigate to a given goal. The dependency on the global information is eliminated by providing only sparse range-finder measurements to the robot. The partially observable planning problem is addressed by splitting it into a hierarchical process. We use convolutional networks to plan locally, and a differentiable memory to provide information about past time steps in the trajectory. These modules, combined in our network architecture, produce globally consistent plans. The sparse reward problem is mitigated by our modified policy gradient algorithm. We model the robots uncertainty with unsupervised tasks to force exploration. The novel architecture we propose with the modified version of the policy gradient algorithm allows our robot to reach the goal in a sample efficient manner, which is orders of magnitude faster than the current state of the art policy gradient algorithm. Simulation and experimental results are provided to validate the proposed approach.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的架构和一种自我监督的策略梯度算法，该算法使用无监督的辅助任务来使移动机器人学习如何导航到给定的目标。通过仅向机器人提供稀疏的测距仪测量来消除对全球信息的依赖性。将部分可观察的规划问题分解为分层过程。我们使用卷积网络进行本地规划，并使用可区分内存来提供有关轨迹中过去时间步骤的信息。这些模块结合我们的网络架构，产生全球一致的计划。我们修改后的策略梯度算法缓解了稀疏奖励问题。我们使用无监督任务对机器人的不确定性进行建模以强制勘探。我们提出的新的架构与政策梯度算法的修改版本相结合，使我们的机器人能够以一种样本有效的方式达到目标，这比现有的政策梯度算法快了几个数量级。提供仿真和实验结果来验证所提出的方法。

##### URL
[http://arxiv.org/abs/1803.01846](http://arxiv.org/abs/1803.01846)

##### PDF
[http://arxiv.org/pdf/1803.01846](http://arxiv.org/pdf/1803.01846)

