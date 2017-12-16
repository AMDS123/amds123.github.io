---
layout: post
title: "Sparse Depth Sensing for Resource-Constrained Robots"
date: 2017-10-15 05:02:51
categories: arXiv_CV
tags: arXiv_CV Sparse Face
author: Fangchang Ma, Luca Carlone, Ulas Ayaz, Sertac Karaman
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the case in which a robot has to navigate in an unknown environment but does not have enough on-board power or payload to carry a traditional depth sensor (e.g., a 3D lidar) and thus can only acquire a few (point-wise) depth measurements. We address the following question: is it possible to reconstruct the geometry of an unknown environment using sparse and incomplete depth measurements? Reconstruction from incomplete data is not possible in general, but when the robot operates in man-made environments, the depth exhibits some regularity (e.g., many planar surfaces with only a few edges); we leverage this regularity to infer depth from a small number of measurements. Our first contribution is a formulation of the depth reconstruction problem that bridges robot perception with the compressive sensing literature in signal processing. The second contribution includes a set of formal results that ascertain the exactness and stability of the depth reconstruction in 2D and 3D problems, and completely characterize the geometry of the profiles that we can reconstruct. Our third contribution is a set of practical algorithms for depth reconstruction: our formulation directly translates into algorithms for depth estimation based on convex programming. In real-world problems, these convex programs are very large and general-purpose solvers are relatively slow. For this reason, we discuss ad-hoc solvers that enable fast depth reconstruction in real problems. The last contribution is an extensive experimental evaluation in 2D and 3D problems, including Monte Carlo runs on simulated instances and testing on multiple real datasets. Empirical results confirm that the proposed approach ensures accurate depth reconstruction, outperforms interpolation-based strategies, and performs well even when the assumption of structured environment is violated.

##### Abstract (translated by Google)
我们考虑机器人必须在未知的环境中导航但没有足够的车载功率或有效载荷来携带传统深度传感器（例如，3D激光雷达）的情况，并且因此只能获得一些（点对点）深度测量。我们解决以下问题：是否可以使用稀疏和不完整的深度测量重建未知环境的几何？不完全数据的重建通常是不可能的，但是当机器人在人造环境中操作时，深度表现出一些规律性（例如，许多平面只有很少的边缘）。我们利用这个规律来从少量测量中推断出深度。我们的第一个贡献是将信号处理中的机器人感知与压缩感知文献相结合的深度重构问题的表述。第二个贡献包括确定二维和三维问题中的深度重建的正确性和稳定性的一组正式结果，并且完整地表征我们可以重建的剖面的几何形状。我们的第三个贡献是一组深度重建的实用算法：我们的公式直接转化为基于凸规划的深度估计算法。在现实世界的问题中，这些凸面程序非常大，通用解算器相对较慢。出于这个原因，我们讨论特殊的解算器，可以在实际问题中快速重建深度。最后一个贡献是2D和3D问题的广泛的实验评估，包括蒙特卡罗在模拟实例上的运行以及在多个实际数据集上的测试。实验结果证实，所提出的方法确保准确的深度重构，优于基于内插的策略，并且即使在违反结构化环境的假设时也表现良好。

##### URL
[https://arxiv.org/abs/1703.01398](https://arxiv.org/abs/1703.01398)

##### PDF
[https://arxiv.org/pdf/1703.01398](https://arxiv.org/pdf/1703.01398)

