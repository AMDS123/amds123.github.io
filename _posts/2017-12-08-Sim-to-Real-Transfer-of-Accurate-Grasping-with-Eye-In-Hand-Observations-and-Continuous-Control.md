---
layout: post
title: "Sim-to-Real Transfer of Accurate Grasping with Eye-In-Hand Observations and Continuous Control"
date: 2017-12-08 22:46:43
categories: arXiv_RO
tags: arXiv_RO Segmentation Face Deep_Learning
author: M. Yan, I. Frosio, S. Tyree, J. Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of deep learning for robotics, we show effective method of training a real robot to grasp a tiny sphere (1.37cm of diameter), with an original combination of system design choices. We decompose the end-to-end system into a vision module and a closed-loop controller module. The two modules use target object segmentation as their common interface. The vision module extracts information from the robot end-effector camera, in the form of a binary segmentation mask of the target. We train it to achieve effective domain transfer by composing real background images with simulated images of the target. The controller module takes as input the binary segmentation mask, and thus is agnostic to visual discrepancies between simulated and real environments. We train our closed-loop controller in simulation using imitation learning and show it is robust with respect to discrepancies between the dynamic model of the simulated and real robot: when combined with eye-in-hand observations, we achieve a 90% success rate in grasping a tiny sphere with a real robot. The controller can generalize to unseen scenarios where the target is moving and even learns to recover from failures.

##### Abstract (translated by Google)
在机器人深度学习的背景下，我们展示了一个有效的方法来训练一个真正的机器人来抓住一个微小的球体（直径1.37厘米），与原来的系统设计选择相结合。我们将端到端系统分解成一个视觉模块和一个闭环控制器模块。这两个模块使用目标对象分割作为它们的通用接口。视觉模块以目标的二进制分割掩模的形式从机器人末端执行器相机提取信息。我们通过将真实的背景图像与目标的模拟图像进行组合来实现有效的域转移。控制器模块将二进制分段掩码作为输入，因此对于模拟和真实环境之间的视觉差异是不可知的。我们使用仿真学习来训练我们的闭环控制器进行仿真，并且显示它对于模拟机器人和真实机器人的动态模型之间的差异是鲁棒的：当与手眼观察相结合时，我们可以实现90％的成功率用真正的机器人抓住一个小球体。控制器可以推广到看不见的场景，即目标正在移动，甚至学习从失败中恢复。

##### URL
[https://arxiv.org/abs/1712.03303](https://arxiv.org/abs/1712.03303)

##### PDF
[https://arxiv.org/pdf/1712.03303](https://arxiv.org/pdf/1712.03303)

