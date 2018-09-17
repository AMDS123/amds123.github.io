---
layout: post
title: "Adaptive Sampling Towards Fast Graph Representation Learning"
date: 2018-09-14 10:33:27
categories: arXiv_CV
tags: arXiv_CV CNN Represenation_Learning Classification
author: Wenbing Huang, Tong Zhang, Yu Rong, Junzhou Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Graph Convolutional Networks (GCNs) have become a crucial tool on learning representations of graph vertices. The main challenge of adapting GCNs on large-scale graphs is the scalability issue that it incurs heavy cost both in computation and memory due to the uncontrollable neighborhood expansion across layers. In this paper, we accelerate the training of GCNs through developing an adaptive layer-wise sampling method. By constructing the network layer by layer in a top-down passway, we sample the lower layer conditioned on the top one, where the sampled neighborhoods are shared by different parent nodes and the over expansion is avoided owing to the fixed-size sampling. More importantly, the proposed sampler is adaptive and applicable for explicit variance reduction, which in turn enhances the training of our method. Furthermore, we propose a novel and economical approach to promote the message passing over distant nodes by applying skip connections. Intensive experiments on several benchmarks verify the effectiveness of our method regarding the classification accuracy while enjoying faster convergence speed.

##### Abstract (translated by Google)
图形卷积网络（GCN）已经成为学习图形顶点表示的重要工具。在大规模图上调整GCN的主要挑战是可扩展性问题，由于跨层的不可控制的邻域扩展，它在计算和存储器中都会产生高成本。在本文中，我们通过开发自适应分层采样方法来加速GCN的培训。通过在自上而下的通道中逐层构建网络，我们对在顶部通道上进行条件化的下层进行采样，其中采样的邻域由不同的父节点共享，并且由于固定大小的采样而避免了过度扩展。更重要的是，所提出的采样器是自适应的，适用于显式方差减少，这反过来又增强了我们方法的训练。此外，我们提出了一种新颖且经济的方法，通过应用跳过连接来促进通过远程节点传递的消息。几个基准测试的密集实验验证了我们的方法在分类准确性方面的有效性，同时享受更快的收敛速度。

##### URL
[http://arxiv.org/abs/1809.05343](http://arxiv.org/abs/1809.05343)

##### PDF
[http://arxiv.org/pdf/1809.05343](http://arxiv.org/pdf/1809.05343)

