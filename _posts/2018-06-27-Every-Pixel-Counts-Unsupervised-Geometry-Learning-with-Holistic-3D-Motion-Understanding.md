---
layout: post
title: "Every Pixel Counts: Unsupervised Geometry Learning with Holistic 3D Motion Understanding"
date: 2018-06-27 16:23:03
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Zhenheng Yang, Peng Wang, Yang Wang, Wei Xu, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to estimate 3D geometry in a single image by watching unlabeled videos via deep convolutional network has made significant process recently. Current state-of-the-art (SOTA) methods, are based on the learning framework of rigid structure-from-motion, where only 3D camera ego motion is modeled for geometry estimation.However, moving objects also exist in many videos, e.g. moving cars in a street scene. In this paper, we tackle such motion by additionally incorporating per-pixel 3D object motion into the learning framework, which provides holistic 3D scene flow understanding and helps single image geometry estimation. Specifically, given two consecutive frames from a video, we adopt a motion network to predict their relative 3D camera pose and a segmentation mask distinguishing moving objects and rigid background. An optical flow network is used to estimate dense 2D per-pixel correspondence. A single image depth network predicts depth maps for both images. The four types of information, i.e. 2D flow, camera pose, segment mask and depth maps, are integrated into a differentiable holistic 3D motion parser (HMP), where per-pixel 3D motion for rigid background and moving objects are recovered. We design various losses w.r.t. the two types of 3D motions for training the depth and motion networks, yielding further error reduction for estimated geometry. Finally, in order to solve the 3D motion confusion from monocular videos, we combine stereo images into joint training. Experiments on KITTI 2015 dataset show that our estimated geometry, 3D motion and moving object masks, not only are constrained to be consistent, but also significantly outperforms other SOTA algorithms, demonstrating the benefits of our approach.

##### Abstract (translated by Google)
学习如何通过深卷积网络观察未标记的视频来估计单个图像中的三维几何图形近来已经成为重要的过程。目前的最新技术（SOTA）方法基于刚性运动结构的学习框架，其中只有3D相机自我运动被建模为几何估计。然而，运动物体也存在于许多视频中，例如，在街头场景中移动汽车。在本文中，我们通过将每像素三维物体运动添加到学习框架中来解决此类运动，该框架提供整体三维场景流程理解并帮助单个图像几何估计。具体来说，如果连续两帧来自视频，我们采用运动网络来预测它们的相对3D相机姿态以及区分移动物体和刚性背景的分割掩模。使用光流网络来估计密集的2D每像素对应关系。单个图像深度网络可以预测两幅图像的深度图。四种类型的信息，即2D流，相机姿态，片段掩模和深度图被集成到可微分整体3D运动解析器（HMP）中，其中用于刚性背景和移动物体的每像素3D运动被恢复。我们设计各种损失w.r.t.用于训练深度和运动网络的两种类型的3D运动，对估计的几何结构产生进一步的误差减小。最后，为了解决单眼视频中的三维运动混淆问题，我们将立体图像结合到联合训练中。 KITTI 2015数据集上的实验表明，我们估计的几何图形，三维运动和移动物体蒙版不仅受限于一致性，而且明显优于其他SOTA算法，体现了我们方法的优势。

##### URL
[http://arxiv.org/abs/1806.10556](http://arxiv.org/abs/1806.10556)

##### PDF
[http://arxiv.org/pdf/1806.10556](http://arxiv.org/pdf/1806.10556)

