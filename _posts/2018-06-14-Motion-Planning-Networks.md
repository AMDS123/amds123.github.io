---
layout: post
title: "Motion Planning Networks"
date: 2018-06-14 23:48:08
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning
author: Ahmed H. Qureshi, Mayur J. Bency, Michael C. Yip
mathjax: true
---

* content
{:toc}

##### Abstract
Fast and efficient motion planning algorithms are crucial for many state-of-the-art robotics applications such as self-driving cars. Existing motion planning methods such as RRT*, A*, and D*, become ineffective as their computational complexity increases exponentially with the dimensionality of the motion planning problem. To address this issue, we present a neural network-based novel planning algorithm which generates end-to-end collision-free paths irrespective of the obstacles' geometry. The proposed method, called MPNet (Motion Planning Network), comprises of a Contractive Autoencoder which encodes the given workspaces directly from a point cloud measurement, and a deep feedforward neural network which takes the workspace encoding, start and goal configuration, and generates end-to-end feasible motion trajectories for the robot to follow. We evaluate MPNet on multiple planning problems such as planning of a point-mass robot, rigid-body, and 7 DOF Baxter robot manipulators in various 2D and 3D environments. The results show that MPNet is not only consistently computationally efficient in all 2D and 3D environments but also show remarkable generalization to completely unseen environments. The results also show that computation time of MPNet consistently remains less than 1 second which is significantly lower than existing state-of-the-art motion planning algorithms. Furthermore, through transfer learning, the MPNet trained in one scenario (e.g., indoor living places) can also quickly adapt to new scenarios (e.g., factory floors) with a little amount of data.

##### Abstract (translated by Google)
快速高效的运动规划算法对许多先进的自动驾驶汽车等机器人应用至关重要。现有的运动规划方法（如RRT *，A *和D *）由于运动规划问题的维数呈指数增长而变得无效。为了解决这个问题，我们提出了一种基于神经网络的小说规划算法，该算法可以生成端到端的无碰撞路径，而不管障碍物的几何形状如何。该方法被称为MPNet（运动规划网络），它包括一个Contractive Autoencoder，它直接从点云测量中对给定的工作空间进行编码，以及一个深度前馈神经网络，该网络采用工作区编码，启动和目标配置，为机器人提供端到端可行的运动轨迹。我们评估MPNet的多个规划问题，例如在各种2D和3D环境中规划点质量机器人，刚体和7自由度Baxter机器人操纵器。结果表明，MPNet不仅在所有2D和3D环境中始终如一地具有计算效率，而且对于完全看不见的环境也显示出显着的一般性。结果还表明，MPNet的计算时间一直保持不到1秒，明显低于现有的最先进的运动规划算法。此外，通过转移学习，在一种情况下训练的MPNet（例如室内生活场所）也可以用少量数据快速适应新的情景（例如工厂车间）。

##### URL
[http://arxiv.org/abs/1806.05767](http://arxiv.org/abs/1806.05767)

##### PDF
[http://arxiv.org/pdf/1806.05767](http://arxiv.org/pdf/1806.05767)

