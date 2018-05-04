---
layout: post
title: "Robust Face Recognition with Deeply Normalized Depth Images"
date: 2018-05-01 16:02:50
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Ziqing Feng, Qijun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Depth information has been proven useful for face recognition. However, existing depth-image-based face recognition methods still suffer from noisy depth values and varying poses and expressions. In this paper, we propose a novel method for normalizing facial depth images to frontal pose and neutral expression and extracting robust features from the normalized depth images. The method is implemented via two deep convolutional neural networks (DCNN), normalization network ($Net_{N}$) and feature extraction network ($Net_{F}$). Given a facial depth image, $Net_{N}$ first converts it to an HHA image, from which the 3D face is reconstructed via a DCNN. $Net_{N}$ then generates a pose-and-expression normalized (PEN) depth image from the reconstructed 3D face. The PEN depth image is finally passed to $Net_{F}$, which extracts a robust feature representation via another DCNN for face recognition. Our preliminary evaluation results demonstrate the superiority of the proposed method in recognizing faces of arbitrary poses and expressions with depth images.

##### Abstract (translated by Google)
深度信息已被证明对人脸识别有用。然而，现有的基于深度图像的人脸识别方法仍然受到深度值嘈杂以及姿势和表情变化的影响。在本文中，我们提出了一种将面部深度图像归一化为正面姿态和中性表达并从归一化深度图像提取鲁棒特征的新方法。该方法通过两个深度卷积神经网络（DCNN），归一化网络（$ Net_ {N} $）和特征提取网络（$ Net_ {F} $）来实现。给定面部深度图像，$ Net_ {N} $首先将其转换为HHA图像，从中通过DCNN重建3D面部。 $ Net_ {N} $然后从重建的3D面部生成姿势 - 表达归一化（PEN）深度图像。 PEN深度图像最终被传递给$ Net_ {F} $，它通过另一个DCNN提取一个强健的特征表示用于人脸识别。我们的初步评估结果证明了所提出的方法在识别具有深度图像的任意姿势和表情的面部方面的优越性。

##### URL
[https://arxiv.org/abs/1805.00406](https://arxiv.org/abs/1805.00406)

##### PDF
[https://arxiv.org/pdf/1805.00406](https://arxiv.org/pdf/1805.00406)

