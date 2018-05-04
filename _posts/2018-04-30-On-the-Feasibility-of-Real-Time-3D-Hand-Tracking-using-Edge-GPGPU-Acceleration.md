---
layout: post
title: "On the Feasibility of Real-Time 3D Hand Tracking using Edge GPGPU Acceleration"
date: 2018-04-30 15:00:40
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Ammar Qammaz, Sokol Kosta, Nikolaos Kyriazis, Antonis Argyros
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents the case study of a non-intrusive porting of a monolithic C++ library for real-time 3D hand tracking, to the domain of edge-based computation. Towards a proof of concept, the case study considers a pair of workstations, a computationally powerful and a computationally weak one. By wrapping the C++ library in Java container and by capitalizing on a Java-based offloading infrastructure that supports both CPU and GPGPU computations, we are able to establish automatically the required server-client workflow that best addresses the resource allocation problem in the effort to execute from the weak workstation. As a result, the weak workstation can perform well at the task, despite lacking the sufficient hardware to do the required computations locally. This is achieved by offloading computations which rely on GPGPU, to the powerful workstation, across the network that connects them. We show the edge-based computation challenges associated with the information flow of the ported algorithm, demonstrate how we cope with them, and identify what needs to be improved for achieving even better performance.

##### Abstract (translated by Google)
本白皮书介绍了用于实时3D手部跟踪的非插入式C ++库的非侵入式移植到基于边缘的计算领域的案例研究。为了证明概念，案例研究考虑了一对工作站，一个计算强大且计算能力较弱的工作站。通过将C ++库封装在Java容器中，并利用基于Java的卸载基础结构（同时支持CPU和GPGPU计算），我们能够自动建立所需的服务器 - 客户端工作流，以最好地解决执行工作中的资源分配问题来自弱工作站。因此，尽管缺乏足够的硬件来在本地执行所需的计算，但弱工作站可以在任务中表现良好。这是通过将依赖GPGPU的计算卸载到功能强大的工作站上，通过连接它们的网络来实现的。我们展示了与移植算法的信息流相关的基于边缘的计算挑战，展示了我们如何处理它们，并确定需要改进哪些方面以实现更好的性能。

##### URL
[https://arxiv.org/abs/1804.11256](https://arxiv.org/abs/1804.11256)

##### PDF
[https://arxiv.org/pdf/1804.11256](https://arxiv.org/pdf/1804.11256)

