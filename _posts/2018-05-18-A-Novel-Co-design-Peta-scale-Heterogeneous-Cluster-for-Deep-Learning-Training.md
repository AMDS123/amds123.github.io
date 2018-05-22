---
layout: post
title: "A Novel Co-design Peta-scale Heterogeneous Cluster for Deep Learning Training"
date: 2018-05-18 23:01:23
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Xin Chen, Hua Zhou, Yuxiang Gao, Yu Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale deep Convolution Neural Networks (CNNs) increasingly demands the computing power. It is key for researchers to own a great powerful computing platform to leverage deep learning (DL) advancing.On the other hand, as the commonly-used accelerator, the commodity GPUs cards of new generations are more and more expensive. Consequently, it is of importance to design an affordable distributed heterogeneous system that provides powerful computational capacity and develop a well-suited software that efficiently utilizes its computational capacity. In this paper, we present our co-design distributed system including a peta-scale GPU cluster, called "Manoa". Based on properties and topology of Manoa, we first propose job server framework and implement it, named "MiMatrix". The central node of MiMatrix, referred to as the job server, undertakes all of controlling, scheduling and monitoring, and I/O tasks without weight data transfer for AllReduce processing in each iteration. Therefore, MiMatrix intrinsically solves the bandwidth bottleneck of central node in parameter server framework that is widely used in distributed DL tasks. Meanwhile, we also propose a new AllReduce algorithm, GPUDirect RDMA-Aware AllReduce~(GDRAA), in which both computation and handshake message are O(1) and the number of synchronization is two in each iteration that is a theoretical minimum number. Owe to the dedicated co-design distributed system, MiMatrix efficiently makes use of the Manoa's computational capacity and bandwidth. We benchmark Manoa Resnet50 and Resenet101 on Imagenet-1K dataset. Some of results have demonstrated state-of-the-art.

##### Abstract (translated by Google)
大规模深度卷积神经网络（CNN）日益要求计算能力。研究人员拥有强大的计算平台以利用深度学习（DL）推进是关键。另一方面，作为常用的加速器，新一代的商品GPU卡越来越昂贵。因此，设计一个负担得起的分布式异构系统非常重要，该系统可提供强大的计算能力，并开发一种能够高效利用其计算能力的非常合适的软件。在本文中，我们展示了我们的协同设计分布式系统，包括一个名为“Manoa”的peta规模GPU集群。基于Manoa的属性和拓扑结构，我们首先提出作业服务器框架并实现它，命名为“MiMatrix”。 MiMatrix的中心节点称为作业服务器，负责所有控制，调度和监视以及I / O任务，无需在每次迭代中处理AllReduce处理的权重数据。因此，MiMatrix从本质上解决了分布式DL任务中广泛使用的参数服务器框架中中心节点的带宽瓶颈问题。同时，我们还提出了一种新的AllReduce算法，GPUDirect RDMA-Aware AllReduce〜（GDRAA），其中计算和握手消息都是O（1），并且在每次迭代中同步数是两个，这是理论上的最小数。由于专门的协同设计分布式系统，MiMatrix高效地利用了Manoa的计算能力和带宽。我们在Imagenet-1K数据集上测试Manoa Resnet50和Resenet101。一些结果已经证明了最先进的技术。

##### URL
[http://arxiv.org/abs/1802.02326](http://arxiv.org/abs/1802.02326)

##### PDF
[http://arxiv.org/pdf/1802.02326](http://arxiv.org/pdf/1802.02326)

