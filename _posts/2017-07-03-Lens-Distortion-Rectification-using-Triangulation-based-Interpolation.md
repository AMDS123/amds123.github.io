---
layout: post
title: "Lens Distortion Rectification using Triangulation based Interpolation"
date: 2017-07-03 20:06:04
categories: arXiv_CV
tags: arXiv_CV
author: Burak Benligiray, Cihan Topal
mathjax: true
---

* content
{:toc}

##### Abstract
Nonlinear lens distortion rectification is a common first step in image processing applications where the assumption of a linear camera model is essential. For rectifying the lens distortion, forward distortion model needs to be known. However, many self-calibration methods estimate the inverse distortion model. In the literature, the inverse of the estimated model is approximated for image rectification, which introduces additional error to the system. We propose a novel distortion rectification method that uses the inverse distortion model directly. The method starts by mapping the distorted pixels to the rectified image using the inverse distortion model. The resulting set of points with subpixel locations are triangulated. The pixel values of the rectified image are linearly interpolated based on this triangulation. The method is applicable to all camera calibration methods that estimate the inverse distortion model and performs well across a large range of parameters.

##### Abstract (translated by Google)
非线性镜头失真校正是图像处理应用中常见的第一步，其中线性相机模型的假设是必不可少的。为了校正镜头失真，需要知道正向失真模型。然而，许多自校准方法估计逆变形模型。在文献中，估计模型的逆矩阵近似于图像校正，这给系统带来了额外的误差。我们提出一种直接使用逆变形模型的新颖的失真校正方法。该方法通过使用逆畸变模型将畸变像素映射到整流图像开始。得到的具有子像素位置的一组点是三角形的。基于这个三角测量对整流图像的像素值进行线性插值。该方法适用于所有的相机校准方法，这些方法可以估计逆向失真模型，并在大范围的参数范围内表现良好。

##### URL
[https://arxiv.org/abs/1611.09559](https://arxiv.org/abs/1611.09559)

##### PDF
[https://arxiv.org/pdf/1611.09559](https://arxiv.org/pdf/1611.09559)

