---
layout: post
title: "Joint Detection and Tracking for Multipath Targets: A Variational Bayesian Approach"
date: 2016-10-27 05:05:42
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Hua Lan, Shuai Sun, Zengfu Wang, Quan Pan, Zhishan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Different from traditional point target tracking systems assuming that a target generates at most one single measurement per scan, there exists a class of multipath target tracking systems where each measurement may originate from the interested target via one of multiple propagation paths or from clutter, while the correspondence among targets, measurements, and propagation paths is unknown. The performance of multipath target tracking systems can be improved if multiple measurements from the same target are effectively utilized, but suffers from two major challenges. The first is multipath detection that detects appearing and disappearing targets automatically, while one target may produce $s$ tracks for $s$ propagation paths. The second is multipath tracking that calculates the target-to-measurement-to-path assignment matrices to estimate target states, which is computationally intractable due to the combinatorial explosion. Based on variational Bayesian framework, this paper introduces a novel probabilistic joint detection and tracking algorithm (JDT-VB) that incorporates data association, path association, state estimation and automatic track management. The posterior probabilities of these latent variables are derived in a closed-form iterative manner, which is effective for dealing with the coupling issue of multipath data association identification risk and state estimation error. Loopy belief propagation (LBP) is exploited to approximate the multipath data association, which significantly reduces the computational cost. The proposed JDT-VB algorithm can simultaneously deal with the track initiation, maintenance, and termination for multiple multipath target tracking with time-varying number of targets, and its performance is verified by a numerical simulation of over-the-horizon radar.

##### Abstract (translated by Google)
从假设目标生成每次扫描至多一个单个测量传统的点目标跟踪系统的不同，存在一类的多径目标跟踪系统，其中每个测量可以从感兴趣的目标通过的多个传播路径中的一个或从杂波起源，而目标，测量和传播路径之间的对应关系是未知的。多目标跟踪系统的性能可以得到改善，如果从同一个目标的多个测量有效利用，但遭受两个主要挑战。第一种是多路径检测，自动检测出现和消失的目标，而一个目标可能为$ s $传播路径产生$ s $轨道。第二种是多路径跟踪，其计算目标到测量到路径的分配矩阵以估计目标状态，由于组合爆炸，这在计算上是棘手的。基于变分贝叶斯框架，本文引入了一种结合数据关联，路径关联，状态估计和自动跟踪管理的新型概率联合检测跟踪算法（JDT-VB）。这些潜变量的后验概率是以闭式迭代方式导出的，对于处理多路径数据关联识别风险和状态估计误差的耦合问题是有效的。利用Loopy置信传播（LBP）来近似多径数据关联，大大降低了计算成本。所提出的JDT-VB算法可以同时与轨道开始，维持和终止多径目标与目标随时间变化的数字跟踪处理，其性能是由超视距雷达的数值模拟验证。

##### URL
[https://arxiv.org/abs/1610.08616](https://arxiv.org/abs/1610.08616)

##### PDF
[https://arxiv.org/pdf/1610.08616](https://arxiv.org/pdf/1610.08616)

