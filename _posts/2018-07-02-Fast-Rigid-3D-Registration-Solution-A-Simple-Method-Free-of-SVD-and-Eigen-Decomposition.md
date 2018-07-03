---
layout: post
title: "Fast Rigid 3D Registration Solution: A Simple Method Free of SVD and Eigen-Decomposition"
date: 2018-07-02 14:49:19
categories: arXiv_RO
tags: arXiv_RO
author: Jin Wu, Ming Liu, Zebo Zhou, Rui Li
mathjax: true
---

* content
{:toc}

##### Abstract
A novel solution is obtained to solve the rigid 3D registration problem, motivated by previous eigen-decomposition approaches. Different from existing solvers, the proposed algorithm does not require sophisticated matrix operations e.g. singular value decomposition or eigenvalue decomposition. Instead, the optimal eigenvector of the point cross-covariance matrix can be computed within several iterations. It is also proven that the optimal rotation matrix can be directly computed for cases without need of quaternion. The simple framework provides very easy approach of integer-implementation on embedded platforms. Simulations on noise-corrupted point clouds have verified the robustness and computation speed of the proposed method. The final results indicate that the proposed algorithm is accurate, robust and owns over $60\% \sim 80\%$ less computation time than representatives. It has also been applied to real-world applications for faster relative robotic navigation.

##### Abstract (translated by Google)
获得了一种新颖的解决方案，以解决由先前的特征分解方法驱动的刚性3D配准问题。与现有的求解器不同，所提出的算法不需要复杂的矩阵运算，例如奇异值分解或特征值分解。相反，可以在几次迭代内计算点交叉协方差矩阵的最优特征向量。还证明了可以在不需要四元数的情况下直接计算最佳旋转矩阵。简单的框架在嵌入式平台上提供了非常简单的整数实现方法。对噪声破坏点云的仿真验证了所提方法的鲁棒性和计算速度。最终结果表明，该算法准确，稳健，并且比代表拥有超过60美元\％\ sim 80 \％$的计算时间。它还应用于实际应用程序，以实现更快的相对机器人导航。

##### URL
[http://arxiv.org/abs/1806.00627](http://arxiv.org/abs/1806.00627)

##### PDF
[http://arxiv.org/pdf/1806.00627](http://arxiv.org/pdf/1806.00627)

