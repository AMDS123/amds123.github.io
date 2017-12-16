---
layout: post
title: "KEPLER: Keypoint and Pose Estimation of Unconstrained Faces by Learning Efficient H-CNN Regressors"
date: 2017-02-16 18:44:59
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation CNN Prediction Detection Recognition
author: Amit Kumar, Azadeh Alavi, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Keypoint detection is one of the most important pre-processing steps in tasks such as face modeling, recognition and verification. In this paper, we present an iterative method for Keypoint Estimation and Pose prediction of unconstrained faces by Learning Efficient H-CNN Regressors (KEPLER) for addressing the face alignment problem. Recent state of the art methods have shown improvements in face keypoint detection by employing Convolution Neural Networks (CNNs). Although a simple feed forward neural network can learn the mapping between input and output spaces, it cannot learn the inherent structural dependencies. We present a novel architecture called H-CNN (Heatmap-CNN) which captures structured global and local features and thus favors accurate keypoint detecion. HCNN is jointly trained on the visibility, fiducials and 3D-pose of the face. As the iterations proceed, the error decreases making the gradients small and thus requiring efficient training of DCNNs to mitigate this. KEPLER performs global corrections in pose and fiducials for the first four iterations followed by local corrections in the subsequent stage. As a by-product, KEPLER also provides 3D pose (pitch, yaw and roll) of the face accurately. In this paper, we show that without using any 3D information, KEPLER outperforms state of the art methods for alignment on challenging datasets such as AFW and AFLW.

##### Abstract (translated by Google)
关键点检测是诸如人脸建模，识别和验证等任务中最重要的预处理步骤之一。在本文中，我们提出了一种用于解决人脸对准问题的迭代方法，用于通过学习有效的H-CNN回归器（KEPLER）对无约束面部的关键点估计和姿态预测。最近的现有技术方法已经通过使用卷积神经网络（CNN）显示了面部关键点检测的改进。虽然一个简单的前馈神经网络可以学习输入和输出空间之间的映射，但它不能学习固有的结构依赖性。我们提出了一种称为H-CNN（热图-CNN）的新型结构，它捕捉结构化的全局和局部特征，因此有利于精确的关键点检测。 HCNN就脸部的可见度，基准和三维姿势进行了联合培训。随着迭代的进行，误差减小使得梯度变小，因此需要对DCNN进行有效的训练以减轻这一点。 KEPLER对前四次迭代的姿态和基准进行全局校正，随后在后续阶段进行局部校正。作为副产品，KEPLER还能精确地提供脸部的3D姿态（俯仰，偏摆和滚动）。在本文中，我们展示了在不使用任何三维信息的情况下，KEPLER比具有挑战性的数据集（如AFW和AFLW）上的对齐方法优越。

##### URL
[https://arxiv.org/abs/1702.05085](https://arxiv.org/abs/1702.05085)

##### PDF
[https://arxiv.org/pdf/1702.05085](https://arxiv.org/pdf/1702.05085)

