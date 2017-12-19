---
layout: post
title: "Parallel Statistical Multi-resolution Estimation"
date: 2015-03-10 09:54:40
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Relation
author: Jan Lebert, Lutz Künneke, Johannes Hagemann, Stephan C. Kramer
mathjax: true
---

* content
{:toc}

##### Abstract
We discuss several strategies to implement Dykstra's projection algorithm on NVIDIA's compute unified device architecture (CUDA). Dykstra's algorithm is the central step in and the computationally most expensive part of statistical multi-resolution methods. It projects a given vector onto the intersection of convex sets. Compared with a CPU implementation our CUDA implementation is one order of magnitude faster. For a further speed up and to reduce memory consumption we have developed a new variant, which we call incomplete Dykstra's algorithm. Implemented in CUDA it is one order of magnitude faster than the CUDA implementation of the standard Dykstra algorithm. As sample application we discuss using the incomplete Dykstra's algorithm as preprocessor for the recently developed super-resolution optical fluctuation imaging (SOFI) method (Dertinger et al. 2009). We show that statistical multi-resolution estimation can enhance the resolution improvement of the plain SOFI algorithm just as the Fourier-reweighting of SOFI. The results are compared in terms of their power spectrum and their Fourier ring correlation (Saxton and Baumeister 1982). The Fourier ring correlation indicates that the resolution for typical second order SOFI images can be improved by about 30 per cent. Our results show that a careful parallelization of Dykstra's algorithm enables its use in large-scale statistical multi-resolution analyses.

##### Abstract (translated by Google)
我们讨论了在NVIDIA的计算统一设备架构（CUDA）上实施Dykstra投影算法的几种策略。 Dykstra算法是统计多分辨率方法的核心步骤，也是计算量最大的部分。它将给定的矢量投影到凸集的交集上。与CPU实现相比，我们的CUDA实现速度要快一个数量级。为了进一步加速并减少内存消耗，我们开发了一个新的变体，我们称之为不完整的Dykstra算法。在CUDA中实现，比标准Dykstra算法的CUDA实现快一个数量级。作为示例应用，我们讨论了使用不完整的Dykstra算法作为最近开发的超分辨率光学波动成像（SOFI）方法（Dertinger等2009）的预处理器。我们表明，统计多分辨率估计可以像SOFI的傅里叶重新加权一样增强纯SOFI算法的分辨率提高。结果在功率谱和傅立叶环相关性方面进行比较（Saxton and Baumeister 1982）。傅里叶环相关性表明典型的二阶SOFI图像的分辨率可以提高约30％。我们的研究结果表明，Dykstra算法的仔细并行化使其能够用于大规模统计多分辨率分析。

##### URL
[https://arxiv.org/abs/1503.03492](https://arxiv.org/abs/1503.03492)

##### PDF
[https://arxiv.org/pdf/1503.03492](https://arxiv.org/pdf/1503.03492)

