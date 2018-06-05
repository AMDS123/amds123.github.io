---
layout: post
title: "Simple Fast Vectorial Solution to The Rigid 3D Registration Problem"
date: 2018-06-02 12:47:38
categories: arXiv_RO
tags: arXiv_RO
author: Jin Wu, Ming Liu, Zebo Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
A novel solution is obtained to solve the rigid 3D registration problem, motivated by previous eigen-decomposition approaches. Different from existing solvers, the proposed algorithm does not require sophisticated matrix operations e.g. singular value decomposition or eigenvalue decomposition. Instead, the optimal eigenvector of the point cross-covariance matrix can be computed within several iterations. It is also proven that the optimal rotation matrix can be directly computed for cases without need of quaternion. The simple framework provides very easy approach of integer-implementation on specialized platforms like FPGA and GPU. Simulations on noise-corrupted point clouds have verified the robustness and computation speed of the proposed method. The final results indicate that the proposed algorithm is accurate, robust and owns over $30\% \sim 80\%$ less computation time than representatives. It has also been applied to real-world applications for faster relative robotic navigation.

##### Abstract (translated by Google)
一个新的解决方案获得解决僵硬的三维配准问题，由以前的特征分解方法驱动。与现有的求解器不同，所提出的算法不需要复杂的矩阵操作，例如，奇异值分解或特征值分解。相反，点互协方差矩阵的最优特征向量可以在几次迭代中计算。也证明了最优旋转矩阵可以直接计算，而不需要四元数的情况。简单的框架提供了在FPGA和GPU等专用平台上实现整数实现的非常简单的方法。对噪声污染点云进行仿真验证了该方法的鲁棒性和计算速度。最后的结果表明，所提出的算法是准确的，鲁棒的，并且比代表的计算时间少了$ 30 \％\ sim 80 \％$。它也被应用于更快的相对机器人导航的实际应用中。

##### URL
[http://arxiv.org/abs/1806.00627](http://arxiv.org/abs/1806.00627)

##### PDF
[http://arxiv.org/pdf/1806.00627](http://arxiv.org/pdf/1806.00627)

