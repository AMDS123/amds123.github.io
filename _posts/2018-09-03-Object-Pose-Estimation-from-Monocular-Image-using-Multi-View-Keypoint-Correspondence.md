---
layout: post
title: "Object Pose Estimation from Monocular Image using Multi-View Keypoint Correspondence"
date: 2018-09-03 11:16:11
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Jogendra Nath Kundu, Rahul M. V., Aditya Ganeshan, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the geometry and pose of objects in 2D images is a fundamental necessity for a wide range of real world applications. Driven by deep neural networks, recent methods have brought significant improvements to object pose estimation. However, they suffer due to scarcity of keypoint/pose-annotated real images and hence can not exploit the object's 3D structural information effectively. In this work, we propose a data-efficient method which utilizes the geometric regularity of intraclass objects for pose estimation. First, we learn pose-invariant local descriptors of object parts from simple 2D RGB images. These descriptors, along with keypoints obtained from renders of a fixed 3D template model are then used to generate keypoint correspondence maps for a given monocular real image. Finally, a pose estimation network predicts 3D pose of the object using these correspondence maps. This pipeline is further extended to a multi-view approach, which assimilates keypoint information from correspondence sets generated from multiple views of the 3D template model. Fusion of multi-view information significantly improves geometric comprehension of the system which in turn enhances the pose estimation performance. Furthermore, use of correspondence framework responsible for the learning of pose invariant keypoint descriptor also allows us to effectively alleviate the data-scarcity problem. This enables our method to achieve state-of-the-art performance on multiple real-image viewpoint estimation datasets, such as Pascal3D+ and ObjectNet3D. To encourage reproducible research, we have released the codes for our proposed approach.

##### Abstract (translated by Google)
了解2D图像中对象的几何和姿势是广泛的实际应用的基本必需品。在深度神经网络的驱动下，最近的方法为对象姿态估计带来了显着的改进。然而，由于关键点/姿势注释的真实图像的稀缺性，它们受到影响，因此无法有效地利用对象的3D结构信息。在这项工作中，我们提出了一种数据有效的方法，利用组内物体的几何规律性进行姿态估计。首先，我们从简单的2D RGB图像中学习对象部分的姿势不变的局部描述符。然后使用这些描述符以及从固定3D模板模型的渲染获得的关键点来生成给定单眼真实图像的关键点对应图。最后，姿势估计网络使用这些对应图预测对象的3D姿势。该流水线进一步扩展到多视图方法，其从来自3D模板模型的多个视图生成的对应集合同化关键点信息。多视图信息的融合显着地改善了系统的几何理解，这反过来增强了姿势估计性能。此外，使用负责学习姿势不变关键点描述符的对应框架也可以有效地缓解数据稀缺问题。这使我们的方法能够在多个真实图像视点估计数据集（如Pascal3D +和ObjectNet3D）上实现最先进的性能。为了鼓励可重复的研究，我们已经发布了我们提出的方法的代码。

##### URL
[http://arxiv.org/abs/1809.00553](http://arxiv.org/abs/1809.00553)

##### PDF
[http://arxiv.org/pdf/1809.00553](http://arxiv.org/pdf/1809.00553)

