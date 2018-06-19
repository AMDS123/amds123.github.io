---
layout: post
title: "High Speed Kernelized Correlation Filters without Boundary Effect"
date: 2018-06-17 16:25:35
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Optimization Relation
author: Ming Tang, Linyu Zheng, Bin Yu, Jinqiao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, correlation filter based trackers (CF trackers) have attracted much attention in vision community because of their top performance in both location and speed. However, the boundary effect imposed by the periodic assumption for the efficient optimization seriously limits their location accuracy. Although there existed many modern works to relax the boundary effect of CF trackers, they all are not able to eliminate the boundary effect thoroughly as well as exploit the kernel trick to improve their location accuracy, and their speeds are reduced greatly. Either relaxing the boundary effect or being able to exploit kernel trick to improve the accuracy, and either relaxing the boundary effect or keeping CF trackers running at high speed have been two dilemmas in the society of visual tracking. To solve these problems, in this paper, we propose a high speed kernel correlation filter without the boundary effect (nBEKCF). Unlike all current CF trackers which exploited real and virtual image patches to train their regression functions, we construct a set of non-orthogonal bases with a group of circulant basic samples and utilize a function defined in Hilbert space and a set of densely sampled, totally real patches to regress a Gaussian goal. This way, the boundary effect is eliminated thoroughly in theory and the kernel trick can be employed naturally. To ensure nBEKCF runs at high speed, we present two efficient algorithms, ACSII and CCIM, to significantly accelerate the evaluation of kernel matrix without employing FFT. By exploiting the circulant structure of basic samples, the efficiency of CCIM in evaluating correlation exceeds that of FFT remarkably. Preliminary experimental results on two public datasets, OTB2013 and OTB2015, show that, without bells and whistles, nBEKCF outperforms representative trackers with hand-crafted features, in the meanwhile, runs at 70 fps on average.

##### Abstract (translated by Google)
最近，基于相关滤波器的跟踪器（CF跟踪器）在视觉领域引起了很多关注，因为它们在位置和速度方面都表现出色。然而，由有效优化的周期性假设施加的边界效应严重限制了它们的定位精度。虽然现在有很多放松CF跟踪器边界效应的工作，但它们都不能彻底消除边界效应，并且利用内核技巧来提高定位精度，并且其速度大大降低。无论是放宽边界效应还是能够利用核心技巧来提高精度，放宽边界效应或保持CF跟踪器高速运行一直是视觉跟踪社会的两大难题。为解决这些问题，本文提出了一种无边界效应的高速核相关滤波器（nBEKCF）。与目前所有利用真实和虚拟图像补丁训练其回归函数的CF跟踪器不同，我们构造了一组具有循环基本样本的非正交基，并利用Hilbert空间中定义的函数和一组密集采样的真正的补丁来回归高斯目标。这样，理论上彻底消除了边界效应，而核心技巧可以自然采用。为了确保nBEKCF以高速运行，我们提出了两种有效的算法ACSII和CCIM，以显着加速核矩阵的评估而不使用FFT。通过利用基本样本的循环结构，CCIM在相关性评估中的效率明显优于FFT。在两个公开数据集OTB2013和OTB2015上的初步实验结果表明，nBEKCF在没有花里胡哨的情况下，胜过具有手工特征的代表性跟踪器，同时平均运行速度为70 fps。

##### URL
[http://arxiv.org/abs/1806.06406](http://arxiv.org/abs/1806.06406)

##### PDF
[http://arxiv.org/pdf/1806.06406](http://arxiv.org/pdf/1806.06406)

