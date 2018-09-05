---
layout: post
title: "Matrix Difference in Pose-Graph Optimization"
date: 2018-09-04 13:41:01
categories: arXiv_RO
tags: arXiv_RO Optimization SLAM
author: Irvin Aloise, Giorgio Grisetti
mathjax: true
---

* content
{:toc}

##### Abstract
Pose-Graph optimization is a crucial component of many modern SLAM systems. Most prominent state of the art systems address this problem by iterative non-linear least squares. Both number of iterations and convergence basin of these approaches depend on the error functions used to describe the problem. The smoother and more convex the error function with respect to perturbations of the state variables, the better the least-squares solver will perform. In this paper we propose an alternative error function obtained by removing some non-linearities from the standard used one - i.e. the geodesic error function. Comparative experiments conducted on common benchmarking datasets confirm that our function is more robust to noise that affects the rotational component of the pose measurements and, thus, exhibits a larger convergence basin than the geodesic. Furthermore, its implementation is relatively easy compared to the geodesic distance. This property leads to rather simple derivatives and nice numerical properties of the Jacobians resulting from the effective computation of the quadratic approximation used by Gauss-Newton algorithm.

##### Abstract (translated by Google)
Pose-Graph优化是许多现代SLAM系统的重要组成部分。最突出的现有技术系统通过迭代非线性最小二乘法解决该问题。这些方法的迭代次数和收敛范围都取决于用于描述问题的误差函数。关于状态变量的扰动，误差函数越平滑和越凸，最小二乘解算器将执行得越好。在本文中，我们提出了一种替代误差函数，该函数是通过从所使用的标准中去除一些非线性而得到的 - 即测地误差函数。在常见基准数据集上进行的对比实验证实，我们的函数对于影响姿势测量的旋转分量的噪声更稳健，因此表现出比测地线更大的会聚盆地。此外，与测地距离相比，其实施相对容易。由于高斯 - 牛顿算法使用的二次近似的有效计算，该性质导致雅各比的相当简单的导数和良好的数值性质。

##### URL
[http://arxiv.org/abs/1809.00952](http://arxiv.org/abs/1809.00952)

##### PDF
[http://arxiv.org/pdf/1809.00952](http://arxiv.org/pdf/1809.00952)

