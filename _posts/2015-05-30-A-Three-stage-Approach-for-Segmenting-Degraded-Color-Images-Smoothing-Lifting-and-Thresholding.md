---
layout: post
title: "A Three-stage Approach for Segmenting Degraded Color Images: Smoothing, Lifting and Thresholding"
date: 2015-05-30 02:53:18
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Xiaohao Cai, Raymond Chan, Mila Nikolova, Tieyong Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a SLaT (Smoothing, Lifting and Thresholding) method with three stages for multiphase segmentation of color images corrupted by different degradations: noise, information loss, and blur. At the first stage, a convex variant of the Mumford-Shah model is applied to each channel to obtain a smooth image. We show that the model has unique solution under the different degradations. In order to properly handle the color information, the second stage is dimension lifting where we consider a new vector-valued image composed of the restored image and its transform in the secondary color space with additional information. This ensures that even if the first color space has highly correlated channels, we can still have enough information to give good segmentation results. In the last stage, we apply multichannel thresholding to the combined vector-valued image to find the segmentation. The number of phases is only required in the last stage, so users can choose or change it all without the need of solving the previous stages again. Experiments demonstrate that our SLaT method gives excellent results in terms of segmentation quality and CPU time in comparison with other state-of-the-art segmentation methods.

##### Abstract (translated by Google)
在本文中，我们提出了一个三阶段的SLaT（Smoothing，Lifting and Thresholding）方法，用于彩色图像的多阶段分割，包括噪声，信息丢失和模糊。在第一阶段，将Mumford-Shah模型的凸变体应用于每个通道以获得平滑的图像。我们证明该模型在不同的退化下具有独特的解决方案。为了正确地处理颜色信息，第二阶段是维度提升，在这里我们考虑一个新的向量值图像组成的恢复图像及其在二次色彩空间的变换与附加信息。这确保即使第一色彩空间具有高度相关的通道，仍然可以获得足够的信息以给出良好的分割结果。在最后阶段，我们将多通道阈值应用于组合的矢量值图像以找到分割。阶段的数量只在最后阶段需要，所以用户可以选择或者改变它，而不需要再次解决前面的阶段。实验证明，与其他最新的分割方法相比，我们的SLaT方法在分割质量和CPU时间方面提供了极好的结果。

##### URL
[https://arxiv.org/abs/1506.00060](https://arxiv.org/abs/1506.00060)

##### PDF
[https://arxiv.org/pdf/1506.00060](https://arxiv.org/pdf/1506.00060)

