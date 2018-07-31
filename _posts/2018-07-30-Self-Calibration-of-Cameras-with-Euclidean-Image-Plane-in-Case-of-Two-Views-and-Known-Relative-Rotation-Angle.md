---
layout: post
title: "Self-Calibration of Cameras with Euclidean Image Plane in Case of Two Views and Known Relative Rotation Angle"
date: 2018-07-30 10:48:56
categories: arXiv_CV
tags: arXiv_CV
author: Evgeniy Martyushev
mathjax: true
---

* content
{:toc}

##### Abstract
The internal calibration of a pinhole camera is given by five parameters that are combined into an upper-triangular $3\times 3$ calibration matrix. If the skew parameter is zero and the aspect ratio is equal to one, then the camera is said to have Euclidean image plane. In this paper, we propose a non-iterative self-calibration algorithm for a camera with Euclidean image plane in case the remaining three internal parameters --- the focal length and the principal point coordinates --- are fixed but unknown. The algorithm requires a set of $N \geq 7$ point correspondences in two views and also the measured relative rotation angle between the views. We show that the problem generically has six solutions (including complex ones). 
 The algorithm has been implemented and tested both on synthetic data and on publicly available real dataset. The experiments demonstrate that the method is correct, numerically stable and robust.

##### Abstract (translated by Google)
针孔摄像机的内部校准由五个参数给出，这五个参数组合成一个上三角形$ 3 \ times 3 $校准矩阵。如果skew参数为零且宽高比等于1，则称摄像机具有欧几里德图像平面。在本文中，我们提出了一种非迭代自校准算法，用于具有欧几里德图像平面的摄像机，以防其余三个内部参数---焦距和主点坐标---固定但未知。该算法在两个视图中需要一组$ N \ geq 7 $点对应关系以及视图之间测量的相对旋转角度。我们证明该问题通常有六种解决方案（包括复杂的解决方案）。
 该算法已在合成数据和公开可用的真实数据集上实施和测试。实验证明该方法是正确的，数值稳定且稳健的。

##### URL
[http://arxiv.org/abs/1807.11279](http://arxiv.org/abs/1807.11279)

##### PDF
[http://arxiv.org/pdf/1807.11279](http://arxiv.org/pdf/1807.11279)

