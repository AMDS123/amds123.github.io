---
layout: post
title: "Joint Face Alignment and 3D Face Reconstruction with Application to Face Recognition"
date: 2017-08-09 06:52:26
categories: arXiv_CV
tags: arXiv_CV Face Relation Recognition Face_Recognition
author: Feng Liu, Qijun Zhao, Xiaoming Liu, Dan Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
Face alignment and 3D face reconstruction are traditionally accomplished as separated tasks. By exploring the strong correlation between 2D landmarks and 3D shapes, in contrast, we propose a joint face alignment and 3D face reconstruction method to simultaneously solve these two problems for 2D face images of arbitrary poses and expressions. This method, based on a summation model of 3D face shapes and cascaded regression in 2D and 3D face shape spaces, iteratively and alternately applies two cascaded regressors, one for updating 2D landmarks and the other for 3D face shape.The 3D face shape and the landmarks are correlated via a 3D-to-2D mapping matrix, which is updated in each iteration to refine the location and visibility of 2D landmarks. Unlike existing methods, the proposed method can fully automatically generate both pose-and-expression-normalized (PEN) and expressive 3D face shapes and localize both visible and invisible 2D landmarks. Based on the PEN 3D face shapes, we devise a method to enhance face recognition accuracy across poses and expressions. Extensive experiments show that the proposed method can achieve the state-of-the-art accuracy in both face alignment and 3D face reconstruction, and benefit face recognition owing to its reconstructed PEN 3D face shapes.

##### Abstract (translated by Google)
传统上，人脸对齐和三维人脸重建是分开的任务。通过探索二维地标与三维形状之间的强相关性，相反，我们提出了联合人脸对齐和三维人脸重建方法，以同时解决任意姿势和表情的二维人脸图像的这两个问题。该方法基于二维和三维人脸形状空间中的三维人脸形状和级联回归求和模型，迭代交替地应用两个级联回归器，一个用于更新二维地标，另一个用于三维人脸形状。三维人脸形状和地标通过3D到2D映射矩阵进行相关，3D矩阵在每次迭代中被更新以改进2D地标的位置和可见性。与现有的方法不同，所提出的方法可以完全自动地生成姿态 - 表达 - 规范化（PEN）和表达的三维人脸形状，并且定位可见和不可见的二维地标。基于笔者的三维人脸形状，我们设计了一种方法来提高人脸识别精度的姿势和表情。大量的实验表明，所提出的方法可以达到人脸对齐和三维人脸重建的最高精度，并且由于其重建的PEN三维人脸形状而有利于人脸识别。

##### URL
[https://arxiv.org/abs/1708.02734](https://arxiv.org/abs/1708.02734)

##### PDF
[https://arxiv.org/pdf/1708.02734](https://arxiv.org/pdf/1708.02734)

