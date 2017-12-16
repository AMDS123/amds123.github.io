---
layout: post
title: "Restoring STM images via Sparse Coding: noise and artifact removal"
date: 2016-10-11 17:37:47
categories: arXiv_CV
tags: arXiv_CV Sparse
author: João P. Oliveira, Ana Bragança, José Bioucas-Dias, Mário Figueiredo, Luís Alcácer, Jorge Morgado, Quirina Ferreira
mathjax: true
---

* content
{:toc}

##### Abstract
In this article, we present a denoising algorithm to improve the interpretation and quality of scanning tunneling microscopy (STM) images. Given the high level of self-similarity of STM images, we propose a denoising algorithm by reformulating the true estimation problem as a sparse regression, often termed sparse coding. We introduce modifications to the algorithm to cope with the existence of artifacts, mainly dropouts, which appear in a structured way as consecutive line segments on the scanning direction. The resulting algorithm treats the artifacts as missing data, and the estimated values outperform those algorithms that substitute the outliers by a local filtering. We provide code implementations for both Matlab and Gwyddion.

##### Abstract (translated by Google)
在本文中，我们提出一种去噪算法来提高扫描隧道显微镜（STM）图像的解释和质量。鉴于STM图像的高度自相似性，我们提出了一种降噪算法，将真正的估计问题重新表示为稀疏回归，通常称为稀疏编码。我们引入对算法的修改来应对伪影的存在，主要是在结构化方式上出现的失落，在扫描方向上作为连续的线段。所得到的算法将伪像视为缺失的数据，并且估计值优于那些通过局部滤波来替代异常值的算法。我们为Matlab和Gwyddion提供代码实现。

##### URL
[https://arxiv.org/abs/1610.03437](https://arxiv.org/abs/1610.03437)

##### PDF
[https://arxiv.org/pdf/1610.03437](https://arxiv.org/pdf/1610.03437)

