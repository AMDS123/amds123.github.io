---
layout: post
title: "3D Facial Expression Reconstruction using Cascaded Regression"
date: 2018-08-17 10:44:48
categories: arXiv_CV
tags: arXiv_CV Face
author: Fanzi Wu, Songnan Li, Tianhao Zhao, King Ngi Ngan, Lv Sheng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel model fitting algorithm for 3D facial expression reconstruction from a single image. Face expression reconstruction from a single image is a challenging task in computer vision. Most state-of-the-art methods fit the input image to a 3D Morphable Model (3DMM). These methods need to solve a stochastic problem and cannot deal with expression and pose variations. To solve this problem, we adopt a 3D face expression model and use a combined feature which is robust to scale, rotation and different lighting conditions. The proposed method applies a cascaded regression framework to estimate parameters for the 3DMM. 2D landmarks are detected and used to initialize the 3D shape and mapping matrices. In each iteration, residues between the current 3DMM parameters and the ground truth are estimated and then used to update the 3D shapes. The mapping matrices are also calculated based on the updated shapes and 2D landmarks. HOG features of the local patches and displacements between 3D landmark projections and 2D landmarks are exploited. Compared with existing methods, the proposed method is robust to expression and pose changes and can reconstruct higher fidelity 3D face shape.

##### Abstract (translated by Google)
本文提出了一种新的单一图像三维人脸表情重建模型拟合算法。从单个图像重建面部表情是计算机视觉中的一项具有挑战性的任务。大多数最先进的方法使输入图像适合3D可变模型（3DMM）。这些方法需要解决随机问题，不能处理表达和姿势变化。为了解决这个问题，我们采用了3D人脸表情模型，并使用了对比例，旋转和不同光照条件具有鲁棒性的组合特征。所提出的方法应用级联回归框架来估计3DMM的参数。检测2D地标并用于初始化3D形状和映射矩阵。在每次迭代中，估计当前3DMM参数与地面实况之间的残差，然后用于更新3D形状。还基于更新的形状和2D地标计算映射矩阵。利用局部斑块的HOG特征以及3D地标投影和2D地标之间的位移。与现有方法相比，该方法对表达和姿态变化具有鲁棒性，可以重建更高保真度的3D人脸形状。

##### URL
[http://arxiv.org/abs/1712.03491](http://arxiv.org/abs/1712.03491)

##### PDF
[http://arxiv.org/pdf/1712.03491](http://arxiv.org/pdf/1712.03491)

