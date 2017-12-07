---
layout: post
title: "A fast nonconvex Compressed Sensing algorithm for highly low-sampled MR images reconstruction"
date: 2017-11-29 19:39:08
categories: arXiv_CV
tags: arXiv_CV
author: Damiana Lazzaro, Elena Loli Piccolomini, Fabiana Zama
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a fast and efficient method for the reconstruction of Magnetic Resonance Images (MRI) from severely under-sampled data. From the Compressed Sensing theory we have mathematically modeled the problem as a constrained minimization problem with a family of non-convex regularizing objective functions depending on a parameter and a least squares data fit constraint. We propose a fast and efficient algorithm, named Fast NonConvex Reweighting (FNCR) algorithm, based on an iterative scheme where the non-convex problem is approximated by its convex linearization and the penalization parameter is automatically updated. The convex problem is solved by a Forward-Backward procedure, where the Backward step is performed by a Split Bregman strategy. Moreover, we propose a new efficient iterative solver for the arising linear systems. We prove the convergence of the proposed FNCR method. The results on synthetic phantoms and real images show that the algorithm is very well performing and computationally efficient, even when compared to the best performing methods proposed in the literature.

##### Abstract (translated by Google)
在本文中，我们提出了一个快速和有效的方法重建磁共振成像（MRI）严重欠采样数据。根据压缩感知理论，我们已经在数学上将该问题建模为具有取决于参数和最小二乘数据拟合约束的非凸正则化目标函数族的约束最小化问题。我们提出了一种快速有效的算法，称为快速非凸重新算法（FNCR），该算法基于迭代方案，其中非凸问题通过其凸线性化来近似并且惩罚参数被自动更新。这个凸问题是通过前向后向程序来解决的，后向步骤是通过分裂布雷格曼策略来执行的。此外，我们提出了一个新的有效的线性系统迭代求解器。我们证明了所提出的FNCR方法的收敛性。合成模型和真实图像的结果表明，即使与文献中提出的最佳执行方法相比，该算法仍然具有良好的执行效率和计算效率。

##### URL
[https://arxiv.org/abs/1711.11075](https://arxiv.org/abs/1711.11075)

##### PDF
[https://arxiv.org/pdf/1711.11075](https://arxiv.org/pdf/1711.11075)

