---
layout: post
title: "Coresets for Kinematic Data: From Theorems to Real-Time Systems"
date: 2017-12-18 14:04:48
categories: arXiv_CV
tags: arXiv_CV
author: Soliman Nasser, Ibrahim Jubran, Dan Feldman
mathjax: true
---

* content
{:toc}

##### Abstract
A coreset (or core-set) of a dataset is its semantic compression with respect to a set of queries, such that querying the (small) coreset provably yields an approximate answer to querying the original (full) dataset. In the last decade, coresets provided breakthroughs in theoretical computer science for approximation algorithms, and more recently, in the machine learning community for learning "Big data". However, we are not aware of real-time systems that compute coresets in a rate of dozens of frames per second. In this paper we suggest a framework to turn theorems to such systems using coresets. We begin with a proof of independent interest, that any set of $n$ matrices in $\mathbb{R}^{d\times d}$ whose sum is $S$, has a positively weighted subset whose sum has the same center of mass (mean) and orientation (left+right singular vectors) as $S$, and consists of $O(dr)$ matrices (independent of $n$), where $r\leq d$ is the rank of $S$. We provide an algorithm that computes this (core) set in one pass over possibly infinite stream of matrices in $d^{O(1)}$ time per matrix insertion. By maintaining such a coreset for kinematic (moving) set of $n$ points, we can run pose-estimation algorithms, such as Kabsch or PnP, on the small coresets, instead of the $n$ points, in real-time using weak devices, while obtaining the same results. This enabled us to implement a low-cost ($&lt;\$100$) IoT wireless system that tracks a toy (and harmless) quadcopter which guides guests to a desired room (in a hospital, mall, hotel, museum, etc.) with no help of additional human or remote controller. We hope that our framework will encourage researchers outside the theoretical community to design and use coresets in future systems and papers. To this end, we provide extensive experimental results on both synthetic and real data, as well as a link to the open code of our system and algorithms.

##### Abstract (translated by Google)
数据集的核心集合（或核心集合）是其关于一组查询的语义压缩，从而查询（小）核心集合可证实地查询原始（完整）数据集的近似答案。在过去的十年里，核心组提供了近似算法理论计算机科学方面的突破，最近在机器学习社区学习“大数据”提供了突破。但是，我们并不知道以每秒几十帧的速度计算核心组的实时系统。在本文中，我们提出了一个使用核心集将定理转化为这种系统的框架。我们从一个独立的兴趣证明开始，$ \ mathbb {R} ^ {d \ times d} $中的$ n $矩阵的任意集合$ S $具有一个正的加权子集，其总和具有相同的中心质量（平均）和方向（左+右奇异向量）为$ S $，并且由$ O（dr）$矩阵（独立于$ n $）组成，其中$ r \ leq d $是$ S $。我们提供了一个算法来计算这个（核心）集合在每个矩阵插入的$ d ^ {O（1）} $ time矩阵的可能无限的流中。通过维护运动学（移动）集合$ n $点的核心集，我们可以在小核心集上运行姿态估计算法（如Kabsch或PnP），而不是$ n $点，实时使用弱设备，同时获得相同的结果。这使我们能够实施一种低成本（$ 100美元）的物联网无线系统，该系统追踪引导客人到达所需房间（医院，商场，酒店，博物馆等）的玩具（无害）四轮飞行器。没有额外的人力或遥控器的帮助。我们希望，我们的框架将鼓励理论界以外的研究人员在未来的系统和论文中设计和使用核心集。为此，我们在合成和实际数据上提供了广泛的实验结果，以及我们的系统和算法的开放代码的链接。

##### URL
[http://arxiv.org/abs/1511.09120](http://arxiv.org/abs/1511.09120)

##### PDF
[http://arxiv.org/pdf/1511.09120](http://arxiv.org/pdf/1511.09120)

