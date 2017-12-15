---
layout: post
title: "Face Hallucination using Linear Models of Coupled Sparse Support"
date: 2015-12-18 16:01:55
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse Face Embedding Relation Recognition
author: Reuben Farrugia, Christine Guillemot
mathjax: true
---

* content
{:toc}

##### Abstract
Most face super-resolution methods assume that low-resolution and high-resolution manifolds have similar local geometrical structure, hence learn local models on the lowresolution manifolds (e.g. sparse or locally linear embedding models), which are then applied on the high-resolution manifold. However, the low-resolution manifold is distorted by the oneto-many relationship between low- and high- resolution patches. This paper presents a method which learns linear models based on the local geometrical structure on the high-resolution manifold rather than on the low-resolution manifold. For this, in a first step, the low-resolution patch is used to derive a globally optimal estimate of the high-resolution patch. The approximated solution is shown to be close in Euclidean space to the ground-truth but is generally smooth and lacks the texture details needed by state-ofthe-art face recognizers. This first estimate allows us to find the support of the high-resolution manifold using sparse coding (SC), which are then used as support for learning a local projection (or upscaling) model between the low-resolution and the highresolution manifolds using Multivariate Ridge Regression (MRR). Experimental results show that the proposed method outperforms six face super-resolution methods in terms of both recognition and quality. These results also reveal that the recognition and quality are significantly affected by the method used for stitching all super-resolved patches together, where quilting was found to better preserve the texture details which helps to achieve higher recognition rates.

##### Abstract (translated by Google)
大多数人脸超分辨方法假设低分辨率和高分辨率流形具有相似的局部几何结构，因此学习低分辨流形（如稀疏或局部线性嵌入模型）上的局部模型，然后将其应用于高分辨率流形。然而，低分辨率流形被低分辨率和高分辨率色块之间的一对多关系扭曲。本文提出了一种在高分辨率流形上而不是在低分辨率流形上基于局部几何结构学习线性模型的方法。为此，在第一步中，使用低分辨率补丁导出高分辨率补丁的全局最优估计。近似的解决方案被证明在欧氏空间中接近真实，但通常是光滑的，并且缺乏现有技术的面部识别器所需的纹理细节。这个第一个估计使我们能够找到使用稀疏编码（SC）的高分辨率流形的支持，然后用这个支持来学习使用多元岭的低分辨率和高分辨率流形之间的局部投影（或放大）模型回归（MRR）。实验结果表明，所提出的方法在识别和质量方面均优于六面超分辨率方法。这些结果还表明，识别和质量显着影响的方法用于缝合所有超分辨的贴片在一起，发现绗缝被更好地保存纹理的细节，有助于实现更高的识别率。

##### URL
[https://arxiv.org/abs/1512.06009](https://arxiv.org/abs/1512.06009)

##### PDF
[https://arxiv.org/pdf/1512.06009](https://arxiv.org/pdf/1512.06009)

