---
layout: post
title: "HDR image reconstruction from a single exposure using deep CNNs"
date: 2017-10-20 10:48:22
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Gabriel Eilertsen, Joel Kronander, Gyorgy Denes, Rafał K. Mantiuk, Jonas Unger
mathjax: true
---

* content
{:toc}

##### Abstract
Camera sensors can only capture a limited range of luminance simultaneously, and in order to create high dynamic range (HDR) images a set of different exposures are typically combined. In this paper we address the problem of predicting information that have been lost in saturated image areas, in order to enable HDR reconstruction from a single exposure. We show that this problem is well-suited for deep learning algorithms, and propose a deep convolutional neural network (CNN) that is specifically designed taking into account the challenges in predicting HDR values. To train the CNN we gather a large dataset of HDR images, which we augment by simulating sensor saturation for a range of cameras. To further boost robustness, we pre-train the CNN on a simulated HDR dataset created from a subset of the MIT Places database. We demonstrate that our approach can reconstruct high-resolution visually convincing HDR results in a wide range of situations, and that it generalizes well to reconstruction of images captured with arbitrary and low-end cameras that use unknown camera response functions and post-processing. Furthermore, we compare to existing methods for HDR expansion, and show high quality results also for image based lighting. Finally, we evaluate the results in a subjective experiment performed on an HDR display. This shows that the reconstructed HDR images are visually convincing, with large improvements as compared to existing methods.

##### Abstract (translated by Google)
相机传感器只能同时捕捉有限范围的亮度，为了创建高动态范围（HDR）图像，通常会组合一组不同的曝光。在本文中，我们解决了预测在饱和图像区域丢失的信息的问题，以便通过单次曝光来重建HDR。我们证明这个问题非常适用于深度学习算法，并且提出了一个深度卷积神经网络（CNN），它是专门设计的，考虑到了预测HDR值的挑战。为了训练CNN，我们收集了一个HDR图像的大数据集，我们通过模拟一系列摄像机的传感器饱和度来增强它们。为了进一步提高鲁棒性，我们在CNN上的一个模拟的HDR数据集上进行了预训练，该数据集是从MIT Places数据库的一个子集创建的。我们证明，我们的方法可以在各种情况下重建高分辨率视觉上令人信服的HDR结果，并且它可以很好地重建使用任意和低端相机拍摄的图像，这些相机使用未知的相机响应函数和后期处理。此外，我们与现有的HDR扩展方法进行比较，并且也为基于图像的照明显示高质量的结果。最后，我们评估在HDR显示器上进行的主观实验的结果。这表明重建的HDR图像在视觉上令人信服，与现有方法相比有了很大的改进。

##### URL
[https://arxiv.org/abs/1710.07480](https://arxiv.org/abs/1710.07480)

##### PDF
[https://arxiv.org/pdf/1710.07480](https://arxiv.org/pdf/1710.07480)

