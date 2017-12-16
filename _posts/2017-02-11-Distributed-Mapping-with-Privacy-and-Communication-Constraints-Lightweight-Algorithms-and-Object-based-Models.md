---
layout: post
title: "Distributed Mapping with Privacy and Communication Constraints: Lightweight Algorithms and Object-based Models"
date: 2017-02-11 16:08:22
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Siddharth Choudhary, Luca Carlone, Carlos Nieto, John Rogers, Henrik I. Christensen, Frank Dellaert
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the following problem: a team of robots is deployed in an unknown environment and it has to collaboratively build a map of the area without a reliable infrastructure for communication. The backbone for modern mapping techniques is pose graph optimization, which estimates the trajectory of the robots, from which the map can be easily built. The first contribution of this paper is a set of distributed algorithms for pose graph optimization: rather than sending all sensor data to a remote sensor fusion server, the robots exchange very partial and noisy information to reach an agreement on the pose graph configuration. Our approach can be considered as a distributed implementation of the two-stage approach of Carlone et al., where we use the Successive Over-Relaxation (SOR) and the Jacobi Over-Relaxation (JOR) as workhorses to split the computation among the robots. As a second contribution, we extend %and demonstrate the applicability of the proposed distributed algorithms to work with object-based map models. The use of object-based models avoids the exchange of raw sensor measurements (e.g., point clouds) further reducing the communication burden. Our third contribution is an extensive experimental evaluation of the proposed techniques, including tests in realistic Gazebo simulations and field experiments in a military test facility. Abundant experimental evidence suggests that one of the proposed algorithms (the Distributed Gauss-Seidel method or DGS) has excellent performance. The DGS requires minimal information exchange, has an anytime flavor, scales well to large teams, is robust to noise, and is easy to implement. Our field tests show that the combined use of our distributed algorithms and object-based models reduces the communication requirements by several orders of magnitude and enables distributed mapping with large teams of robots in real-world problems.

##### Abstract (translated by Google)
我们考虑以下问题：一个机器人小组被部署在一个未知的环境中，并且必须协作地构建该地区的地图，而没有可靠的通信基础设施。现代测绘技术的骨干是姿态图优化，它可以估算机器人的轨迹，从中可以轻松地建立地图。本文的第一个贡献是一组用于姿态图优化的分布式算法：机器人不是将所有的传感器数据发送到远程传感器融合服务器，而是交换非常局部和噪声的信息，以便就姿态图配置达成一致。我们的方法可以被认为是Carlone等人的两阶段方法的分布式实现，其中我们使用连续过度松弛（SOR）和Jacobi过度松弛（JOR）作为主要工具来分割机器人之间的计算。作为第二个贡献，我们扩展％并证明了所提出的分布式算法适用于基于对象的地图模型。使用基于对象的模型避免了原始传感器测量（例如，点云）的交换，进一步减少了通信负担。我们的第三个贡献是对所提出的技术的广泛的实验评估，包括在现实的Gazebo模拟中的测试和在军事测试设施中的现场实验。丰富的实验证据表明，所提出的算法之一（分布式Gauss-Seidel方法或DGS）具有优异的性能。 DGS只需要极少的信息交换，具有随时随地的乐趣，适合大型团队，噪音强劲，易于实施。我们的现场测试表明，我们的分布式算法和基于对象的模型的结合使用将通信需求降低了几个数量级，并且使得大型机器人队伍能够在实际问题中进行分布式映射。

##### URL
[https://arxiv.org/abs/1702.03435](https://arxiv.org/abs/1702.03435)

##### PDF
[https://arxiv.org/pdf/1702.03435](https://arxiv.org/pdf/1702.03435)

