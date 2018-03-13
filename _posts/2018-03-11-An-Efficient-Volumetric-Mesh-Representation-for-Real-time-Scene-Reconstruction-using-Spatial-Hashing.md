---
layout: post
title: "An Efficient Volumetric Mesh Representation for Real-time Scene Reconstruction using Spatial Hashing"
date: 2018-03-11 11:55:55
categories: arXiv_RO
tags: arXiv_RO
author: Wei Dong, Jieqi Shi, Weijie Tang, Xin Wang, Hongbin Zha
mathjax: true
---

* content
{:toc}

##### Abstract
Mesh plays an indispensable role in dense real-time reconstruction essential in robotics. Efforts have been made to maintain flexible data structures for 3D data fusion, yet an efficient incremental framework specifically designed for online mesh storage and manipulation is missing. We propose a novel framework to compactly generate, update, and refine mesh for scene reconstruction upon a volumetric representation. Maintaining a spatial-hashed field of cubes, we distribute vertices with continuous value on discrete edges that support O(1) vertex accessing and forbid memory redundancy. By introducing Hamming distance in mesh refinement, we further improve the mesh quality regarding the triangle type consistency with a low cost. Lock-based and lock-free operations were applied to avoid thread conflicts in GPU parallel computation. Experiments demonstrate that the mesh memory consumption is significantly reduced while the running speed is kept in the online reconstruction process.

##### Abstract (translated by Google)
网格在机器人技术中必不可少的密集实时重建中起着不可或缺的作用。已经做出努力来保持用于3D数据融合的灵活数据结构，但是没有专门设计用于在线网格存储和操纵的高效增量框架。我们提出了一个新颖的框架来紧凑地生成，更新和细化网格，以便在体积表示时进行场景重建。维护立方体的空间散列场，我们在离散边上分配具有连续值的顶点，以支持O（1）顶点访问并禁止内存冗余。通过在网格细化中引入汉明距离，我们以低成本进一步提高关于三角形类型一致性的网格质量。应用基于锁和无锁操作来避免GPU并行计算中的线程冲突。实验表明，网络内存消耗显着减少，而运行速度保持在在线重建过程中。

##### URL
[https://arxiv.org/abs/1803.03949](https://arxiv.org/abs/1803.03949)

##### PDF
[https://arxiv.org/pdf/1803.03949](https://arxiv.org/pdf/1803.03949)

