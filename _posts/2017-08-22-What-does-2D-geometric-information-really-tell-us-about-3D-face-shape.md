---
layout: post
title: "What does 2D geometric information really tell us about 3D face shape?"
date: 2017-08-22 16:21:13
categories: arXiv_CV
tags: arXiv_CV Face Quantitative
author: Anil Bas, William A. P. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
A face image contains geometric cues in the form of configurational information and contours that can be used to estimate 3D face shape. While it is clear that 3D reconstruction from 2D points is highly ambiguous if no further constraints are enforced, one might expect that the face-space constraint solves this problem. We show that this is not the case and that geometric information is an ambiguous cue. There are two sources for this ambiguity. The first is that, within the space of 3D face shapes, there are flexibility modes that remain when some parts of the face are fixed. The second occurs only under perspective projection and is a result of perspective transformation as camera distance varies. Two different faces, when viewed at different distances, can give rise to the same 2D geometry. To demonstrate these ambiguities, we develop new algorithms for fitting a 3D morphable model to 2D landmarks or contours under either orthographic or perspective projection and show how to compute flexibility modes for both cases. We show that both fitting problems can be posed as a separable nonlinear least squares problem and solved efficiently. We provide quantitative and qualitative evidence that the ambiguity exists in synthetic data and real images.

##### Abstract (translated by Google)
人脸图像包含可用于估计3D人脸形状的配置信息和轮廓形式的几何线索。虽然很明显，如果没有进一步的约束被强制执行，2D点的三维重建是非常模糊的，但人们可能会期望面空间约束解决了这个问题。我们表明，情况并非如此，几何信息是一个模棱两可的线索。这个歧义有两个来源。首先，在三维脸形的空间内，当脸部的某些部分被固定时，存在灵活模式。第二个仅在透视投影下出现，并且是相机距离变化时透视变换的结果。在不同距离观察时，两个不同的面可以产生相同的二维几何。为了演示这些模糊性，我们开发了一种新的算法，用于在正交或透视投影下拟合三维形变模型到二维地标或轮廓，并展示如何计算两种情况下的灵活模式。我们表明，两个拟合问题都可以作为一个可分离的非线性最小二乘问题，并有效地解决。我们提供了定量和定性证据，证明合成数据和真实图像存在模糊性。

##### URL
[https://arxiv.org/abs/1708.06703](https://arxiv.org/abs/1708.06703)

##### PDF
[https://arxiv.org/pdf/1708.06703](https://arxiv.org/pdf/1708.06703)

