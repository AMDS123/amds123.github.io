---
layout: post
title: "Optimization-Based Collision Avoidance"
date: 2018-06-10 23:50:09
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Xiaojing Zhang, Alexander Liniger, Francesco Borrelli
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel method for reformulating non-differentiable collision avoidance constraints into smooth nonlinear constraints using strong duality of convex optimization. We focus on a controlled object whose goal is to avoid obstacles while moving in an n-dimensional space. The proposed reformulation does not introduce approximations, and applies to general obstacles and controlled objects that can be represented in an n-dimensional space as the finite union of convex sets. Furthermore, we connect our results with the notion of signed distance, which is widely used in traditional trajectory generation algorithms. Our method can be used in generic navigation and trajectory planning tasks, and the smoothness property allows the use of general-purpose gradient- and Hessian-based optimization algorithms. Finally, in case a collision cannot be avoided, our framework allows us to find "least-intrusive" trajectories, measured in terms of penetration. We demonstrate the efficacy of our framework on a quadcopter navigation and automated parking problem, and our numerical experiments suggest that the proposed methods enable real-time optimization-based trajectory planning problems in tight environments. Source code of our implementation is provided at https://github.com/XiaojingGeorgeZhang/OBCA.

##### Abstract (translated by Google)
本文提出了一种利用凸优化的强对偶性将非可微碰撞避免约束转化为平滑非线性约束的新方法。我们专注于一个受控对象，其目标是在n维空间中移动时避开障碍物。所提出的重新配置不引入近似值，并且适用于可以在n维空间中表示为凸集的有限联合的一般障碍和受控对象。此外，我们将我们的结果与传统轨迹生成算法中广泛使用的带符号距离概念联系起来。我们的方法可用于通用导航和轨迹规划任务，并且smoothness属性允许使用通用梯度和基于Hessian的优化算法。最后，如果碰撞无法避免，我们的框架使我们能够找到“渗透率最低”的轨迹，以渗透率来衡量。我们演示了我们的框架在四轴飞行器导航和自动停车问题上的功效，我们的数值实验表明，所提出的方法可以在紧密环境中实现基于实时优化的轨迹规划问题。 https://github.com/XiaojingGeorgeZhang/OBCA提供了我们实现的源代码。

##### URL
[http://arxiv.org/abs/1711.03449](http://arxiv.org/abs/1711.03449)

##### PDF
[http://arxiv.org/pdf/1711.03449](http://arxiv.org/pdf/1711.03449)

