---
layout: post
title: "Real-time Joint Tracking of a Hand Manipulating an Object from RGB-D Input"
date: 2016-10-16 17:11:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking Optimization Classification Quantitative
author: Srinath Sridhar, Franziska Mueller, Michael Zollhöfer, Dan Casas, Antti Oulasvirta, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time simultaneous tracking of hands manipulating and interacting with external objects has many potential applications in augmented reality, tangible computing, and wearable computing. However, due to difficult occlusions, fast motions, and uniform hand appearance, jointly tracking hand and object pose is more challenging than tracking either of the two separately. Many previous approaches resort to complex multi-camera setups to remedy the occlusion problem and often employ expensive segmentation and optimization steps which makes real-time tracking impossible. In this paper, we propose a real-time solution that uses a single commodity RGB-D camera. The core of our approach is a 3D articulated Gaussian mixture alignment strategy tailored to hand-object tracking that allows fast pose optimization. The alignment energy uses novel regularizers to address occlusions and hand-object contacts. For added robustness, we guide the optimization with discriminative part classification of the hand and segmentation of the object. We conducted extensive experiments on several existing datasets and introduce a new annotated hand-object dataset. Quantitative and qualitative results show the key advantages of our method: speed, accuracy, and robustness.

##### Abstract (translated by Google)
实时同步跟踪操纵和与外部物体交互的手在增强现实，有形计算和可穿戴计算中具有许多潜在的应用。然而，由于困难的遮挡，快速的运动和统一的手感，联合跟踪手和物体的姿势比分别追踪两者中的任何一个更具挑战性。许多以前的方法诉诸复杂的多相机设置来纠正遮挡问题，并且经常采用昂贵的分割和优化步骤，这使得实时跟踪成为不可能。在本文中，我们提出了一个使用单个商品RGB-D相机的实时解决方案。我们的方法的核心是一个三维铰接高斯混合对齐策略，针对手对象跟踪，允许快速姿态优化。对齐能量使用新颖的正规化器来解决遮挡和手对象的接触。为了增加鲁棒性，我们引导手的区分部分分类和对象分割的优化。我们对几个现有的数据集进行了广泛的实验，并引入了一个新的带注释的手对象数据集。定量和定性的结果显示了我们的方法的关键优势：速度，准确性和鲁棒性。

##### URL
[https://arxiv.org/abs/1610.04889](https://arxiv.org/abs/1610.04889)

##### PDF
[https://arxiv.org/pdf/1610.04889](https://arxiv.org/pdf/1610.04889)

