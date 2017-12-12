---
layout: post
title: "3D Facial Expression Reconstruction using Cascaded Regression"
date: 2017-12-10 09:53:21
categories: arXiv_CV
tags: arXiv_CV Face
author: Fanzi Wu, Songnan Li, Tianhao Zhao, King Ngi Ngan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel model fitting algorithm for 3D facial expression reconstruction from a single image. Face expression reconstruction from a single image is a challenging task in computer vision. Most state-of-the-art methods fit the input image to a 3D Morphable Model (3DMM). These methods need to solve a stochastic problem and cannot deal with expression and pose variations. To solve this problem, we adopt a 3D face expression model and use a combined feature which is robust to scale, rotation and different lighting conditions. The proposed method applies a cascaded regression framework to estimate parameters for the 3DMM. 2D landmarks are detected and used to initialize the 3D shape and mapping matrices. In each iteration, residues between the current 3DMM parameters and the ground truth are estimated and then used to update the 3D shapes. The mapping matrices are also calculated based on the updated shapes and 2D landmarks. HOG features of the local patches and displacements between 3D landmark projections and 2D landmarks are exploited. Compared with existing methods, the proposed method is robust to expression and pose changes and can reconstruct higher fidelity 3D face shape.

##### Abstract (translated by Google)
本文提出了一种新的基于单幅图​​像的三维人脸表情重建模型拟合算法。从单个图像重建脸部表情是计算机视觉中的一个具有挑战性的任务。大多数最先进的方法将输入图像拟合成3D形变模型（3DMM）。这些方法需要解决一个随机问题，不能处理表达和构造变化。为了解决这个问题，我们采用了一个三维人脸表情模型，并且使用了一个对尺度，旋转和不同光照条件具有鲁棒性的组合特征。所提出的方法应用级联回归框架来估计3DMM的参数。 2D地标被检测并用于初始化3D形状和映射矩阵。在每次迭代中，估计当前3DMM参数与地面真实之间的残差，然后用于更新3D形状。映射矩阵也是基于更新的形状和2D地标来计算的。利用3D地标投影和2D地标之间的局部贴片和位移的HOG特征。与现有方法相比，该方法对表情和姿态变化具有鲁棒性，能够重建较高逼真度的三维人脸形状。

##### URL
[http://arxiv.org/abs/1712.03491](http://arxiv.org/abs/1712.03491)

##### PDF
[http://arxiv.org/pdf/1712.03491](http://arxiv.org/pdf/1712.03491)

