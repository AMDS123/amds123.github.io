---
layout: post
title: "MiMatrix: A Massively Distributed Deep Learning Framework on a Petascale High-density Heterogeneous Cluster"
date: 2018-02-07 07:20:42
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Gradient_Descent
author: Xin Chen, Hua Zhou, Yuxiang Gao, Yu Zhu, Dongyan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a co-designed petascale high-density GPU cluster to expedite distributed deep learning training with synchronous Stochastic Gradient Descent~(SSGD). This architecture of our heterogeneous cluster is inspired by Harvard architecture. Regarding to different roles in the system, nodes are configured as different specifications. Based on the topology of the whole system's network and properties of different types of nodes, we develop and implement a novel job server parallel software framework, named by "\textit{MiMatrix}", for distributed deep learning training. Compared to the parameter server framework, in which parameter server is a bottleneck of data transfer in AllReduce algorithm of SSGD, the job server undertakes all of controlling, scheduling and monitoring tasks without model data transfer. In MiMatrix, we propose a novel GPUDirect Remote direct memory access~(RDMA)-aware parallel algorithm of AllReucde executed by computing servers, which both computation and handshake message are $O(1)$ at each epoch

##### Abstract (translated by Google)
在本文中，我们提出了一个共同设计的千兆级高密度GPU集群，以加速分布式深度学习训练和同步随机梯度下降（SSGD）。我们的异构集群体系结构受哈佛架构的启发。关于系统中的不同角色，节点被配置为不同的规格。基于整个系统网络的拓扑结构和不同类型节点的属性，开发并实现了一种新型的作业服务器并行软件框架，由“\ textit {MiMatrix}”命名，用于分布式深度学习培训。与参数服务器框架相比，参数服务器是SSGD的AllReduce算法中数据传输的瓶颈，作业服务器负责所有的控制，调度和监视任务，而不需要模型数据传输。在MiMatrix中，我们提出了一个由计算服务器执行的新型GPUDirect远程直接存储器访问（RDMA）并行算法AllReucde，在每个时期计算和握手消息都是$ O（1）$

##### URL
[https://arxiv.org/abs/1802.02326](https://arxiv.org/abs/1802.02326)

##### PDF
[https://arxiv.org/pdf/1802.02326](https://arxiv.org/pdf/1802.02326)

