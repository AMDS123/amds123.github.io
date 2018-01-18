---
layout: post
title: "A modified fuzzy C means algorithm for shading correction in craniofacial CBCT images"
date: 2018-01-17 14:54:39
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation
author: Awais Ashfaq, Jonas Adler
mathjax: true
---

* content
{:toc}

##### Abstract
CBCT images suffer from acute shading artifacts primarily due to scatter. Numerous image-domain correction algorithms have been proposed in the literature that use patient-specific planning CT images to estimate shading contributions in CBCT images. However, in the context of radiosurgery applications such as gamma knife, planning images are often acquired through MRI which impedes the use of polynomial fitting approaches for shading correction. We present a new shading correction approach that is independent of planning CT images. Our algorithm is based on the assumption that true CBCT images follow a uniform volumetric intensity distribution per material, and scatter perturbs this uniform texture by contributing cupping and shading artifacts in the image domain. The framework is a combination of fuzzy C-means coupled with a neighborhood regularization term and Otsu's method. Experimental results on artificially simulated craniofacial CBCT images are provided to demonstrate the effectiveness of our algorithm. Spatial non-uniformity is reduced from 16% to 7% in soft tissue and from 44% to 8% in bone regions. With shading-correction, thresholding based segmentation accuracy for bone pixels is improved from 85% to 91% when compared to thresholding without shading-correction. The proposed algorithm is thus practical and qualifies as a plug and play extension into any CBCT reconstruction software for shading correction.

##### Abstract (translated by Google)
CBCT图像主要由于散射而受到严重阴影伪影的影响。在文献中已经提出许多图像域校正算法，其使用患者特定的计划CT图像来估计CBCT图像中的阴影贡献。然而，在诸如伽马刀之类的放射外科应用的情况下，通常通过MRI获取计划图像，这妨碍了使用多项式拟合方法进行阴影校正。我们提出了一种独立于计划CT图像的新的阴影校正方法。我们的算法是基于以下假设：真实的CBCT图像遵循每种材料的均匀的体积强度分布，并且通过在图像域中贡献拔罐和阴影伪影，散射干扰这种均匀的纹理。该框架结合了模糊C均值和邻域正则化项以及Otsu方法。提供了人工模拟颅面CBCT图像的实验结果，以证明我们的算法的有效性。软组织中的空间不均匀性从16％降低到7％，在骨骼区域中从44％降低到8％。通过阴影校正，与没有阴影校正的阈值处理相比，基于阈值的骨骼像素分割精度从85％提高到91％。所提出的算法因此是实用的，并且作为用于阴影校正的任何CBCT重建软件的即插即用扩展。

##### URL
[http://arxiv.org/abs/1801.05694](http://arxiv.org/abs/1801.05694)

##### PDF
[http://arxiv.org/pdf/1801.05694](http://arxiv.org/pdf/1801.05694)

