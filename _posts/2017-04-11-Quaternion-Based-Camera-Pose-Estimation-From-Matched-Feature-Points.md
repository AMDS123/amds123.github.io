---
layout: post
title: "Quaternion Based Camera Pose Estimation From Matched Feature Points"
date: 2017-04-11 18:41:05
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation
author: Kaveh Fathian, J. Pablo Ramirez-Paredes, Emily A. Doucette, J. Willard Curtis, Nicholas R. Gans
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel solution to the camera pose estimation problem, where rotation and translation of a camera between two views are estimated from matched feature points in the images. The camera pose estimation problem is traditionally solved via algorithms that are based on the essential matrix or the Euclidean homography. With six or more feature points in general positions in the space, essential matrix based algorithms can recover a unique solution. However, such algorithms fail when points are on critical surfaces (e.g., coplanar points) and homography should be used instead. By formulating the problem in quaternions and decoupling the rotation and translation estimation, our proposed algorithm works for all point configurations. Using both simulated and real world images, we compare the estimation accuracy of our algorithm with some of the most commonly used algorithms. Our method is shown to be more robust to noise and outliers. For the benefit of community, we have made the implementation of our algorithm available online and free.

##### Abstract (translated by Google)
我们提出了一个新的解决方案的相机姿态估计问题，其中两个视图之间的相机旋转和平移估计从图像匹配的特征点。照相机姿态估计问题传统上是通过基于基本矩阵或欧几里德单应性的算法来解决的。在空间的一般位置有六个或更多的特征点，基本的基于矩阵的算法可以恢复一个独特的解决方案。然而，当点位于关键表面（例如共面点）并且应该使用单应性时，这样的算法失败。通过制定四元数的问题，解旋转和平移估计，我们提出的算法适用于所有的点配置。使用模拟和现实世界的图像，我们比较我们的算法与一些最常用的算法的估计精度。我们的方法被证明对噪声和异常值更强大。为了社区的利益，我们已经实现了我们的算法在线免费。

##### URL
[https://arxiv.org/abs/1704.02672](https://arxiv.org/abs/1704.02672)

##### PDF
[https://arxiv.org/pdf/1704.02672](https://arxiv.org/pdf/1704.02672)

