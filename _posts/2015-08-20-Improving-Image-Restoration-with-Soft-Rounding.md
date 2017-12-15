---
layout: post
title: "Improving Image Restoration with Soft-Rounding"
date: 2015-08-20 17:04:34
categories: arXiv_CV
tags: arXiv_CV Knowledge Quantitative
author: Xing Mei, Honggang Qi, Bao-Gang Hu, Siwei Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
Several important classes of images such as text, barcode and pattern images have the property that pixels can only take a distinct subset of values. This knowledge can benefit the restoration of such images, but it has not been widely considered in current restoration methods. In this work, we describe an effective and efficient approach to incorporate the knowledge of distinct pixel values of the pristine images into the general regularized least squares restoration framework. We introduce a new regularizer that attains zero at the designated pixel values and becomes a quadratic penalty function in the intervals between them. When incorporated into the regularized least squares restoration framework, this regularizer leads to a simple and efficient step that resembles and extends the rounding operation, which we term as soft-rounding. We apply the soft-rounding enhanced solution to the restoration of binary text/barcode images and pattern images with multiple distinct pixel values. Experimental results show that soft-rounding enhanced restoration methods achieve significant improvement in both visual quality and quantitative measures (PSNR and SSIM). Furthermore, we show that this regularizer can also benefit the restoration of general natural images.

##### Abstract (translated by Google)
几种重要的图像类型（如文本，条形码和图案图像）具有像素只能取值的不同子集的特性。这种知识可以有益于这些图像的恢复，但在目前的恢复方法中还没有得到广泛的考虑。在这项工作中，我们描述了一种有效和高效的方法，将原始图像的不同像素值的知识结合到一般正则化最小二乘恢复框架中。我们引入一个新的正规化器，在指定的像素值处达到零，并且在它们之间的间隔中变成二次惩罚函数。当纳入规则化最小二乘修复框架时，这个正规化器导致了一个简单而有效的步骤，类似于并扩大了舍入操作，我们称之为软化。我们将软修整增强解决方案应用于具有多个不同像素值的二进制文本/条形码图像和图案图像的恢复。实验结果表明，软圆化增强修复方法在视觉质量和定量测量（PSNR和SSIM）方面均取得显着改善。此外，我们表明，这个正规化者也可以有利于恢复一般的自然图像。

##### URL
[https://arxiv.org/abs/1508.05046](https://arxiv.org/abs/1508.05046)

##### PDF
[https://arxiv.org/pdf/1508.05046](https://arxiv.org/pdf/1508.05046)

