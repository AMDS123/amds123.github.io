---
layout: post
title: "Avalon: Building an Operating System for Robotcenter"
date: 2018-05-02 11:47:19
categories: arXiv_RO
tags: arXiv_RO
author: Yuan Xu, Zhiyuan Yan, Sa Wang, Cheng Yang, Qingsai Xiao, Yungang Bao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper envisions a scenario that hundreds of heterogeneous robots form a robotcenter which can be shared by multiple users and used like a single powerful robot to perform complex tasks. However, current multi-robot systems are either unable to manage heterogeneous robots or unable to support multiple concurrent users. Inspired by the design of modern datacenter OSes, we propose Avalon, a robot operating system with two-level scheduling scheme which is widely adopted in datacenters for Internet services and cloud computing. Specifically, Avalon integrates three important features together: (1) Instead of allocating a whole robot, Avalon classifies fine-grained robot resources into three categories to distinguish which fine-grained resources can be shared by multi-robot frameworks simultaneously. (2) Avalon adopts a location based resource allocation policy to substantially reduce scheduling overhead. (3) Avalon enables robots to offload computation intensive tasks to the clouds.We have implemented and evaluated Avalon on robots on both simulated environments and real world.

##### Abstract (translated by Google)
本文设想了一个场景，数百个异构机器人形成一个机器人中心，可以由多个用户共享，并像一个强大的机器人一样用于执行复杂的任务。但是，目前的多机器人系统无法管理异构机器人或无法支持多个并发用户。受到现代数据中心操作系统设计的启发，我们提出了Avalon，这是一种具有两级调度方案的机器人操作系统，在互联网服务和云计算的数据中心广泛采用。具体而言，Avalon将三个重要特性集成在一起：（1）Avalon不是分配整个机器人，而是将细粒度机器人资源分为三类，以区分哪些细粒度资源可以被多机器人框架同时共享。 （2）Avalon采用基于位置的资源分配策略来大幅降低调度开销。 （3）Avalon使机器人能够将计算密集型任务卸载到云端。我们已经在模拟环境和现实世界中的机器人上实施并评估了Avalon。

##### URL
[https://arxiv.org/abs/1805.00745](https://arxiv.org/abs/1805.00745)

##### PDF
[https://arxiv.org/pdf/1805.00745](https://arxiv.org/pdf/1805.00745)

