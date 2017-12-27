---
layout: post
title: "Server assisted distributed cooperative localization over unreliable communication links"
date: 2017-12-24 18:41:39
categories: arXiv_RO
tags: arXiv_RO
author: Solmaz S. Kia, Jonathan Hechtbauer, David Gogokhiya, Sonia Martinez
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the problem of cooperative localization (CL) using inter-robot measurements for a group of networked robots with limited on-board resources. We propose a novel recursive algorithm in which each robot localizes itself in a global coordinate frame by local dead reckoning, and opportunistically corrects its pose estimate whenever it receives a relative measurement update message from a server. The computation and storage cost per robot in terms of the size of the team is of order O(1), and the robots are only required to transmit information when they are involved in a relative measurement. The server also only needs to compute and transmit update messages when it receives an inter-robot measurement. We show that under perfect communication, our algorithm is an alternative but exact implementation of a joint CL for the entire team via Extended Kalman Filter (EKF). The perfect communication however is not a hard requirement. In fact, we show that our algorithm is intrinsically robust with respect to communication failures, with formal guarantees that the updated estimates of the robots receiving the update message are of minimum variance in a first-order approximate sense at that given timestep. We demonstrate the performance of the algorithm in simulation and experiments.

##### Abstract (translated by Google)
本文考虑了在机器人资源有限的情况下，使用跨机器人测量的一组联网机器人的协作定位（CL）问题。我们提出了一种新的递归算法，其中每个机器人通过局部航位推算在全局坐标系中定位自己，并且每当从服务器接收到相对测量更新消息时就机会地校正其姿态估计。每个机器人的团队规模计算和存储成本为O（1），机器人只有在参与相关测量时才需要传输信息。当服务器接收到机器人间测量时，也只需要计算和发送更新消息。我们表明，在完美的沟通下，我们的算法是通过扩展卡尔曼滤波器（EKF）对整个团队进行联合CL的替代但精确的实现。完美的交流并不是一个硬性的要求。事实上，我们表明，我们的算法在通信故障方面本质上是稳健的，具有形式上的保证，即在给定时间步长的情况下，接收到更新消息的机器人的更新估计在一阶近似意义上具有最小方差。我们证明了算法在仿真和实验中的性能。

##### URL
[http://arxiv.org/abs/1608.00609](http://arxiv.org/abs/1608.00609)

##### PDF
[http://arxiv.org/pdf/1608.00609](http://arxiv.org/pdf/1608.00609)

