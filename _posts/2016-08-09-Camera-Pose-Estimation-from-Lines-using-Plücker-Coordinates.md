---
layout: post
title: "Camera Pose Estimation from Lines using Plücker Coordinates"
date: 2016-08-09 14:58:34
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Bronislav Přibyl, Pavel Zemčík, Martin Čadík
mathjax: true
---

* content
{:toc}

##### Abstract
Correspondences between 3D lines and their 2D images captured by a camera are often used to determine position and orientation of the camera in space. In this work, we propose a novel algebraic algorithm to estimate the camera pose. We parameterize 3D lines using Pl\"ucker coordinates that allow linear projection of the lines into the image. A line projection matrix is estimated using Linear Least Squares and the camera pose is then extracted from the matrix. An algebraic approach to handle mismatched line correspondences is also included. The proposed algorithm is an order of magnitude faster yet comparably accurate and robust to the state-of-the-art, it does not require initialization, and it yields only one solution. The described method requires at least 9 lines and is particularly suitable for scenarios with 25 and more lines, as also shown in the results.

##### Abstract (translated by Google)
通常使用相机捕获的3D线和它们的2D图像之间的对应关系来确定相机在空间中的位置和方向。在这项工作中，我们提出了一种新的代数算法来估计相机姿态。我们使用Pl \ ucker坐标参数化三维线，允许线条线性投影到图像中，使用线性最小二乘法估计线条投影矩阵，然后从矩阵中提取摄像机姿态。所提出的算法比现有技术快一个数量级但相当精确和稳健，不需要初始化，而且只产生一个解决方案，所描述的方法至少需要9条线和特别适用于25行或更多行的情况，结果如图所示。

##### URL
[https://arxiv.org/abs/1608.02824](https://arxiv.org/abs/1608.02824)

##### PDF
[https://arxiv.org/pdf/1608.02824](https://arxiv.org/pdf/1608.02824)

