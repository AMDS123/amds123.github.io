---
layout: post
title: "Cooperative Robot Localization Using Event-triggered Estimation"
date: 2018-02-20 21:47:34
categories: arXiv_RO
tags: arXiv_RO Relation
author: Michael Ouimet, David Iglesias, Nisar Ahmed, Sonia Martinez
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a novel communication-spare cooperative localization algorithm for a team of mobile unmanned robotic vehicles. Exploiting an event-based estimation paradigm, robots only send measurements to neighbors when the expected innovation for state estimation is high. Since agents know the event-triggering condition for measurements to be sent, the lack of a measurement is thus also informative and fused into state estimates. The robots use a Covariance Intersection (CI) mechanism to occasionally synchronize their local estimates of the full network state. In addition, heuristic balancing dynamics on the robots' CI-triggering thresholds ensure that, in large diameter networks, the local error covariances remains below desired bounds across the network. Simulations on both linear and nonlinear dynamics/measurement models show that the event-triggering approach achieves nearly optimal state estimation performance in a wide range of operating conditions, even when using only a fraction of the communication cost required by conventional full data sharing. The robustness of the proposed approach to lossy communications, as well as the relationship between network topology and CI-based synchronization requirements, are also examined.

##### Abstract (translated by Google)
本文描述了一种用于移动无人驾驶机器人车队的新型通信 - 备用合作定位算法。利用基于事件的评估范例，当预期的状态估计创新很高时，机器人仅向邻居发送测量结果。由于代理知道要发送的测量的事件触发条件，因此缺少测量也是信息性的并且融合到状态估计中。机器人使用协方差相交（CI）机制来偶尔同步其对整个网络状态的本地估计。另外，机器人CI触发阈值的启发式平衡动力学确保了在大直径网络中局部误差协方差保持低于整个网络的期望边界。对线性和非线性动态/测量模型的仿真表明，即使仅使用传统全面数据共享所需的通信成本的一小部分，事件触发方法也可在广泛的操作条件下实现接近最佳的状态估计性能。所提出的有损通信方法的鲁棒性以及网络拓扑和基于CI的同步要求之间的关系也被检查。

##### URL
[http://arxiv.org/abs/1802.07346](http://arxiv.org/abs/1802.07346)

##### PDF
[http://arxiv.org/pdf/1802.07346](http://arxiv.org/pdf/1802.07346)

