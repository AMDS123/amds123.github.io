---
layout: post
title: "Nighttime Haze Removal with Illumination Correction"
date: 2016-06-05 04:15:53
categories: arXiv_CV
tags: arXiv_CV
author: Jing Zhang, Yang Cao, Zengfu Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Haze removal is important for computational photography and computer vision applications. However, most of the existing methods for dehazing are designed for daytime images, and cannot always work well in the nighttime. Different from the imaging conditions in the daytime, images captured in nighttime haze condition may suffer from non-uniform illumination due to artificial light sources, which exhibit low brightness/contrast and color distortion. In this paper, we present a new nighttime hazy imaging model that takes into account both the non-uniform illumination from artificial light sources and the scattering and attenuation effects of haze. Accordingly, we propose an efficient dehazing algorithm for nighttime hazy images. The proposed algorithm includes three sequential steps. i) It enhances the overall brightness by performing a gamma correction step after estimating the illumination from the original image. ii) Then it achieves a color-balance result by performing a color correction step after estimating the color characteristics of the incident light. iii) Finally, it remove the haze effect by applying the dark channel prior and estimating the point-wise environmental light based on the previous illumination-balance result. Experimental results show that the proposed algorithm can achieve illumination-balance and haze-free results with good color rendition ability.

##### Abstract (translated by Google)
去除雾霾对于计算摄影和计算机视觉应用是重要的。然而，大多数现有的去雾方法都是为白天图像而设计的，并且在夜间不能一直很好地工作。与白天的成像条件不同，在夜间雾霾状况下拍摄的图像可能由于人造光源而导致不均匀的照明，这些人造光源表现出低亮度/对比度和颜色失真。在本文中，我们提出了一个新的夜间朦胧成像模型，考虑到人造光源的非均匀照明以及雾度的散射和衰减效应。因此，我们提出了一个高效的夜间模糊图像去雾算法。所提出的算法包括三个连续的步骤。 i）通过在估计来自原始图像的照明之后执行伽马校正步骤来提高整体亮度。 ii）然后通过在估计入射光的颜色特性之后执行颜色校正步骤来实现颜色平衡结果。 iii）最后，通过预先应用暗通道来消除雾霾效应，并且基于之前的照度平衡结果来估计逐点环境光。实验结果表明，该算法能够达到光照平衡，无霾效果，色彩还原能力强。

##### URL
[https://arxiv.org/abs/1606.01460](https://arxiv.org/abs/1606.01460)

##### PDF
[https://arxiv.org/pdf/1606.01460](https://arxiv.org/pdf/1606.01460)

