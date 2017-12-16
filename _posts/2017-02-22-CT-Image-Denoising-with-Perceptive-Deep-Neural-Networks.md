---
layout: post
title: "CT Image Denoising with Perceptive Deep Neural Networks"
date: 2017-02-22 21:50:55
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Qingsong Yang, Pingkun Yan, Mannudeep K. Kalra, Ge Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Increasing use of CT in modern medical practice has raised concerns over associated radiation dose. Reduction of radiation dose associated with CT can increase noise and artifacts, which can adversely affect diagnostic confidence. Denoising of low-dose CT images on the other hand can help improve diagnostic confidence, which however is a challenging problem due to its ill-posed nature, since one noisy image patch may correspond to many different output patches. In the past decade, machine learning based approaches have made quite impressive progress in this direction. However, most of those methods, including the recently popularized deep learning techniques, aim for minimizing mean-squared-error (MSE) between a denoised CT image and the ground truth, which results in losing important structural details due to over-smoothing, although the PSNR based performance measure looks great. In this work, we introduce a new perceptual similarity measure as the objective function for a deep convolutional neural network to facilitate CT image denoising. Instead of directly computing MSE for pixel-to-pixel intensity loss, we compare the perceptual features of a denoised output against those of the ground truth in a feature space. Therefore, our proposed method is capable of not only reducing the image noise levels, but also keeping the critical structural information at the same time. Promising results have been obtained in our experiments with a large number of CT images.

##### Abstract (translated by Google)
在现代医学实践中越来越多地使用CT引起了对相关辐射剂量的担忧。减少与CT有关的辐射剂量会增加噪声和伪影，这可能对诊断信心产生不利影响。另一方面，低剂量CT图像的去噪有助于提高诊断的可信度，然而由于其不适宜的性质，这是一个具有挑战性的问题，因为一个噪声图像补丁可能对应于许多不同的输出补丁。在过去的十年中，基于机器学习的方法在这个方向上取得了相当可观的进展。然而，包括最近普及的深度学习技术在内的这些方法大部分旨在最小化去噪的CT图像与地面真实之间的均方误差（MSE），这导致由于过度平滑而丢失重要的结构细节，尽管基于PSNR的性能指标看起来不错。在这项工作中，我们引入一个新的感知相似性度量作为一个深层卷积神经网络的目标函数，以方便CT图像去噪。我们不是直接计算像素到像素强度损失的MSE，而是将特征空间中去噪输出的感知特征与基本事实的感知特征进行比较。因此，我们提出的方法不仅能够降低图像噪声水平，而且能够同时保持关键的结构信息。在我们的大量CT图像实验中已经获得了有希望的结果。

##### URL
[https://arxiv.org/abs/1702.07019](https://arxiv.org/abs/1702.07019)

##### PDF
[https://arxiv.org/pdf/1702.07019](https://arxiv.org/pdf/1702.07019)

