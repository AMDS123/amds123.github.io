---
layout: post
title: "An analysis of the factors affecting keypoint stability in scale-space"
date: 2015-11-26 19:09:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Ives Rey-Otero, Jean-Michel Morel, Mauricio Delbracio
mathjax: true
---

* content
{:toc}

##### Abstract
The most popular image matching algorithm SIFT, introduced by D. Lowe a decade ago, has proven to be sufficiently scale invariant to be used in numerous applications. In practice, however, scale invariance may be weakened by various sources of error inherent to the SIFT implementation affecting the stability and accuracy of keypoint detection. The density of the sampling of the Gaussian scale-space and the level of blur in the input image are two of these sources. This article presents a numerical analysis of their impact on the extracted keypoints stability. Such an analysis has both methodological and practical implications, on how to compare feature detectors and on how to improve SIFT. We show that even with a significantly oversampled scale-space numerical errors prevent from achieving perfect stability. Usual strategies to filter out unstable detections are shown to be inefficient. We also prove that the effect of the error in the assumption on the initial blur is asymmetric and that the method is strongly degraded in presence of aliasing or without a correct assumption on the camera blur.

##### Abstract (translated by Google)
D.Lowe十年前推出的最流行的图像匹配算法SIFT已经被证明具有足够的尺度不变性以用于许多应用中。然而，实际上，SIFT实现所固有的各种误差来源会影响关键点检测的稳定性和准确性，从而可能削弱尺度不变性。高斯尺度空间的采样密度和输入图像中的模糊水平是这些源中的两个。本文提出了一个数值分析它们对提取关键点稳定性的影响。这样的分析既具有方法上的实际意义，又具有如何比较特征检测器以及如何改善SIFT。我们表明，即使是显着过采样的尺度空间数值错误也不能实现完美的稳定性。通常的筛选不稳定检测的策略是低效的。我们还证明了假设中的误差对初始模糊的影响是不对称的，并且该方法在存在混叠的情况下强烈退化或者在相机模糊上没有正确的假设。

##### URL
[https://arxiv.org/abs/1511.08478](https://arxiv.org/abs/1511.08478)

##### PDF
[https://arxiv.org/pdf/1511.08478](https://arxiv.org/pdf/1511.08478)

