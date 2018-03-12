---
layout: post
title: "Model Predictive Control for Autonomous Driving considering Actuator Dynamics"
date: 2018-03-09 11:55:52
categories: arXiv_RO
tags: arXiv_RO
author: Mithun Babu, Raghu Ram Theerthala, Arun Kumar Singh, Bharath Gopalakrishnan, K.Madhava Kirshna
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new model predictive control (MPC) formulation for autonomous driving. The novelty of our formulation stems from the following new results. Firstly, we adopt an alternating minimization approach wherein linear velocities and angular accelerations are alternately optimized. We show that in contrast to the joint formulation, the alternating minimization better exploits the structure of the problem. This in turn translates to reduction in computation time. Secondly, our MPC formulation incorporates the time dependent non-linear actuator dynamics which relates commanded velocity input to the actual body velocity of the vehicle. This added complexity improves the predictive component of MPC resulting in improved margin of inter-vehicle distance during maneuvers like overtaking, lane-change etc. Although, past works have also incorporated actuator dynamics within MPC, there has been very few attempts towards coupling actuator dynamics to collision avoidance constraints through the non-holonomic motion model of the vehicle and analyzing the resulting behavior. We test our formulation on a simulated environment and use metrics like inter-vehicle distance, velocity overshoot to demonstrate its usefulness.

##### Abstract (translated by Google)
在本文中，我们提出了一种用于自主驾驶的新型模型预测控制（MPC）公式。我们的配方的新颖性源于以下新的结果。首先，我们采用交替最小化方法，其中线性速度和角加速度交替优化。我们证明，与联合公式相比，交替最小化更好地利用了问题的结构。这反过来又减少了计算时间。其次，我们的MPC公式结合了时间相关的非线性执行器动力学，它将命令的速度输入与车辆的实际车体速度相关联。这种增加的复杂性改进了MPC的预测分量，导致在诸如超车，车道变换等机动过程中车辆间距离的改善。尽管过去的作品也将MPC内的执行器动力学结合起来，但很少尝试将执行器动力学通过车辆的非完整运动模型来避免碰撞约束并分析所得到的行为。我们在模拟环境中测试我们的公式，并使用像车辆间距离，速度超调等指标来证明其有用性。

##### URL
[http://arxiv.org/abs/1803.03478](http://arxiv.org/abs/1803.03478)

##### PDF
[http://arxiv.org/pdf/1803.03478](http://arxiv.org/pdf/1803.03478)

