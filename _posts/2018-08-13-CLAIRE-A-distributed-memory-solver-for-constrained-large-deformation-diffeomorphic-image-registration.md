---
layout: post
title: "CLAIRE: A distributed-memory solver for constrained large deformation diffeomorphic image registration"
date: 2018-08-13 22:59:25
categories: arXiv_CV
tags: arXiv_CV
author: Andreas Mang, Amir Gholami, Christos Davatzikos, George Biros
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce CLAIRE, a distributed-memory algorithm and software for solving constrained large deformation diffeomorphic image registration problems in three dimensions. We invert for a stationary velocity field that parameterizes the deformation map. Our solver is based on a globalized, preconditioned, inexact reduced space Gauss--Newton--Krylov scheme. 
 We exploit state-of-the-art techniques in scientific computing to develop an effective solver that scales to thousand of distributed memory nodes on high-end clusters. Our improved, parallel implementation features parameter-, scale-, and grid-continuation schemes to speedup the computations and reduce the likelihood to get trapped in local minima. We also implement an improved preconditioner for the reduced space Hessian to speedup the convergence. 
 We test registration performance on synthetic and real data. We demonstrate registration accuracy on 16 neuroimaging datasets. We compare the performance of our scheme against different flavors of the DEMONS algorithm for diffeomorphic image registration. We study convergence of our preconditioner and our overall algorithm. We report scalability results on state-of-the-art supercomputing platforms. We demonstrate that we can solve registration problems for clinically relevant data sizes in two to four minutes on a standard compute node with 20 cores, attaining excellent data fidelity. With the present work we achieve a speedup of (on average) 5x with a peak performance of up to 17x compared to our former work.

##### Abstract (translated by Google)
我们介绍了CLAIRE，一种分布式存储算法和软件，用于解决三维约束大变形微分图像配准问题。我们反演一个参数化变形图的静止速度场。我们的求解器基于全球化，预处理，不精确的缩小空间Gauss  -  Newton  -  Krylov方案。
 我们利用科学计算领域最先进的技术开发出一种有效的求解器，可以扩展到高端集群上的数千个分布式存储节点。我们改进的并行实现具有参数，比例和网格延续方案，可加速计算并降低陷入局部最小值的可能性。我们还为减少空间Hessian实现了一个改进的预处理器，以加速收敛。
 我们测试合成和真实数据的注册性能。我们证明了16个神经影像数据集的配准精度。我们将我们的方案的性能与DEMONS算法的不同风格进行比较，以进行微差异图像配准。我们研究了预处理器和整体算法的收敛性。我们报告了最先进的超级计算平台的可扩展性结果。我们证明，我们可以在具有20个核心的标准计算节点上，在2至4分钟内解决临床相关数据大小的注册问题，从而获得出色的数据保真度。通过目前的工作，我们实现了（平均）5倍的加速，与之前的工作相比，峰值性能高达17倍。

##### URL
[http://arxiv.org/abs/1808.04487](http://arxiv.org/abs/1808.04487)

##### PDF
[http://arxiv.org/pdf/1808.04487](http://arxiv.org/pdf/1808.04487)

