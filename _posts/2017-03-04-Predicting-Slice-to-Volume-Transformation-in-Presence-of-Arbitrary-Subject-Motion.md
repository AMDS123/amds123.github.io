---
layout: post
title: "Predicting Slice-to-Volume Transformation in Presence of Arbitrary Subject Motion"
date: 2017-03-04 12:32:52
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Quantitative
author: Benjamin Hou, Amir Alansary, Steven McDonagh, Alice Davidson, Mary Rutherford, Jo V. Hajnal, Daniel Rueckert, Ben Glocker, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to solve a fundamental problem in intensity-based 2D/3D registration, which concerns the limited capture range and need for very good initialization of state-of-the-art image registration methods. We propose a regression approach that learns to predict rotation and translations of arbitrary 2D image slices from 3D volumes, with respect to a learned canonical atlas co-ordinate system. To this end, we utilize Convolutional Neural Networks (CNNs) to learn the highly complex regression function that maps 2D image slices into their correct position and orientation in 3D space. Our approach is attractive in challenging imaging scenarios, where significant subject motion complicates reconstruction performance of 3D volumes from 2D slice data. We extensively evaluate the effectiveness of our approach quantitatively on simulated MRI brain data with extreme random motion. We further demonstrate qualitative results on fetal MRI where our method is integrated into a full reconstruction and motion compensation pipeline. With our CNN regression approach we obtain an average prediction error of 7mm on simulated data, and convincing reconstruction quality of images of very young fetuses where previous methods fail. We further discuss applications to Computed Tomography and X-ray projections. Our approach is a general solution to the 2D/3D initialization problem. It is computationally efficient, with prediction times per slice of a few milliseconds, making it suitable for real-time scenarios.

##### Abstract (translated by Google)
本文旨在解决基于强度的二维/三维配准中的一个基本问题，其涉及有限的捕获范围以及需要对最先进的图像配准方法进行非常好的初始化。我们提出了一个回归方法，学习预测任意二维图像切片从三维卷的旋转和翻译，相对于学习规范阿特拉斯坐标系统。为此，我们利用卷积神经网络（CNN）来学习高度复杂的回归函数，将2D图像切片映射到3D空间中正确的位置和方向。我们的方法在具有挑战性的成像场景中具有吸引力，其中重要的对象运动使来自2D切片数据的3D体积的重建性能复杂化我们广泛评估我们的方法定量模拟MRI脑部数据与极端的随机运动的有效性。我们进一步展示胎儿MRI的定性结果，其中我们的方法被整合到完整的重建和运动补偿管道中。使用我们的CNN回归方法，我们获得了模拟数据的7mm的平均预测误差，以及说服以前的方法失败的非常年轻胎儿的图像的重建质量。我们进一步讨论应用到计算机断层扫描和X射线投影。我们的方法是2D / 3D初始化问题的通用解决方案。它在计算上是高效的，每片的预测时间为几毫秒，使其适用于实时场景。

##### URL
[https://arxiv.org/abs/1702.08891](https://arxiv.org/abs/1702.08891)

##### PDF
[https://arxiv.org/pdf/1702.08891](https://arxiv.org/pdf/1702.08891)

