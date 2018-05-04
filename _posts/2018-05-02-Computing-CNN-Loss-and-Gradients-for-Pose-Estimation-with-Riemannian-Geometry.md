---
layout: post
title: "Computing CNN Loss and Gradients for Pose Estimation with Riemannian Geometry"
date: 2018-05-02 21:17:03
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Deep_Learning Prediction Detection
author: Benjamin Hou, Nina Miolane, Bishesh Khanal, Matthew C.H. Lee, Amir Alansary, Steven McDonagh, Jo V. Hajnal, Daniel Rueckert, Ben Glocker, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
Pose estimation, i.e. predicting a 3D rigid transformation with respect to a fixed co-ordinate frame in, SE(3), is an omnipresent problem in medical image analysis with applications such as: image rigid registration, anatomical standard plane detection, tracking and device/camera pose estimation. Deep learning methods often parameterise a pose with a representation that separates rotation and translation. As commonly available frameworks do not provide means to calculate loss on a manifold, regression is usually performed using the L2-norm independently on the rotation's and the translation's parameterisations, which is a metric for linear spaces that does not take into account the Lie group structure of SE(3). In this paper, we propose a general Riemannian formulation of the pose estimation problem. We propose to train the CNN directly on SE(3) equipped with a left-invariant Riemannian metric, coupling the prediction of the translation and rotation defining the pose. At each training step, the ground truth and predicted pose are elements of the manifold, where the loss is calculated as the Riemannian geodesic distance. We then compute the optimisation direction by back-propagating the gradient with respect to the predicted pose on the tangent space of the manifold SE(3) and update the network weights. We thoroughly evaluate the effectiveness of our loss function by comparing its performance with popular and most commonly used existing methods, on tasks such as image-based localisation and intensity-based 2D/3D registration. We also show that hyper-parameters, used in our loss function to weight the contribution between rotations and translations, can be intrinsically calculated from the dataset to achieve greater performance margins.

##### Abstract (translated by Google)
姿态估计，即在SE（3）中关于固定坐标系预测3D刚性变换是医学图像分析中的无所不在的问题，其应用如图像刚性配准，解剖标准平面检测，跟踪和装置/相机姿态估计。深度学习方法通​​常用一个表示来分隔旋转和平移的姿势。由于通常可用的框架不提供计算流形上的损失的方法，所以回归通常独立于旋转和翻译的参数化来使用L2规范来执行，该参数是线性空间的度量，其不考虑李群结构SE（3）。在本文中，我们提出了姿态估计问题的一般黎曼公式。我们建议直接在SE（3）上训练配备左不变黎曼度量的CNN，将翻译和旋转的预测结合起来定义姿态。在每个训练步骤中，地面实况和预测姿态都是流形的元素，其中损失按照黎曼测地距离计算。然后，我们通过相对于流形SE（3）的切线空间上的预测姿态向后传播梯度来计算优化方向，并更新网络权重。我们通过比较其性能和流行和最常用的现有方法，对诸如基于图像的定位和基于强度的2D / 3D配准等任务，彻底评估了我们损失函数的有效性。我们还表明，在我们的损失函数中使用的超参数来加权旋转和平移之间的贡献，可以根据数据集内在地计算出来，以实现更高的性能余量。

##### URL
[http://arxiv.org/abs/1805.01026](http://arxiv.org/abs/1805.01026)

##### PDF
[http://arxiv.org/pdf/1805.01026](http://arxiv.org/pdf/1805.01026)

