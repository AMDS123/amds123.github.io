---
layout: post
title: "BB8: A Scalable, Accurate, Robust to Partial Occlusion Method for Predicting the 3D Poses of Challenging Objects without Using Depth"
date: 2017-03-31 13:56:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Pose_Estimation CNN Detection
author: Mahdi Rad, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel method for 3D object detection and pose estimation from color images only. We first use segmentation to detect the objects of interest in 2D even in presence of partial occlusions and cluttered background. By contrast with recent patch-based methods, we rely on a "holistic" approach: We apply to the detected objects a Convolutional Neural Network (CNN) trained to predict their 3D poses in the form of 2D projections of the corners of their 3D bounding boxes for the pose of objects' parts. This, however, is not sufficient for handling objects from the recent T-LESS dataset: These objects exhibit an axis of rotational symmetry, and the similarity of two images of such an object under two different poses makes training the CNN challenging. We solve this problem by restricting the range of poses used for training, and by introducing a classifier to identify the range of a pose at run-time before estimating it. We also use an optional additional step that refines the predicted poses for hand pose estimation. We improve the state-of-the-art on the LINEMOD dataset from 73.7% to 89.3% of correctly registered RGB frames. We are also the first to report results on the Occlusion dataset using color images only. We obtain 54% of frames passing the Pose 6D criterion on average on several sequences of the T-LESS dataset, compared to the 67% of the state-of-the-art on the same sequences which uses both color and depth. The full approach is also scalable, as a single network can be trained for multiple objects simultaneously.

##### Abstract (translated by Google)
我们引入了一种新的方法来进行三维物体检测和姿态估计从彩色图像只。我们首先使用分割来检测2D中感兴趣的对象，即使在部分遮挡和混乱的背景下也是如此。与最近基于补丁的方法相比，我们依赖于“整体”方法：我们将被卷积的神经网络（CNN）应用于检测到的对象，以3D立体角的2D投影形式预测其3D姿态对象的部分姿势框。但是，这对于处理最近的T-LESS数据集中的对象是不够的：这些对象表现出一个旋转对称轴，两个不同姿势下这样一个对象的两幅图像的相似性使得训练CNN具有挑战性。我们通过限制用于训练的姿势的范围来解决这个问题，并且在估计之前引入分类器以在运行时识别姿势的范围。我们还使用一个可选的附加步骤来改进手势估计的预测姿态。我们将LINEMOD数据集的最新技术从正确注册的RGB帧的73.7％提高到了89.3％。我们也是第一个使用彩色图像报告Occlusion数据集的结果。我们在T-LESS数据集的几个序列上平均获得了通过Pose 6D准则的54％的帧，相比之下，在使用颜色和深度的相同序列中的67％的水平。完整的方法也是可扩展的，因为单个网络可以同时训练多个对象。

##### URL
[https://arxiv.org/abs/1703.10896](https://arxiv.org/abs/1703.10896)

##### PDF
[https://arxiv.org/pdf/1703.10896](https://arxiv.org/pdf/1703.10896)

