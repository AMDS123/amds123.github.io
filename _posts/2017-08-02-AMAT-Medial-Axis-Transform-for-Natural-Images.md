---
layout: post
title: "AMAT: Medial Axis Transform for Natural Images"
date: 2017-08-02 23:21:18
categories: arXiv_CV
tags: arXiv_CV Detection
author: Stavros Tsogkas, Sven Dickinson
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Appearance-MAT (AMAT), a generalization of the medial axis transform for natural images, that is framed as a weighted geometric set cover problem. We make the following contributions: i) we extend previous medial point detection methods for color images, by associating each medial point with a local scale; ii) inspired by the invertibility property of the binary MAT, we also associate each medial point with a local encoding that allows us to invert the AMAT, reconstructing the input image; iii) we describe a clustering scheme that takes advantage of the additional scale and appearance information to group individual points into medial branches, providing a shape decomposition of the underlying image regions. In our experiments, we show state-of-the-art performance in medial point detection on Berkeley Medial AXes (BMAX500), a new dataset of medial axes based on the BSDS500 database, and good generalization on the SK506 and WH-SYMMAX datasets. We also measure the quality of reconstructed images from BMAX500, obtained by inverting their computed AMAT. Our approach delivers significantly better reconstruction quality with respect to three baselines, using just 10% of the image pixels. Our code and annotations are available at this https URL .

##### Abstract (translated by Google)
我们引入了Appearance-MAT（AMAT），这是一种对自然图像进行中轴变换的泛化，它被构建为一个加权几何集覆盖问题。我们做出如下贡献：i）通过将每个中间点与局部尺度联系起来，我们扩展了先前的彩色图像的中间点检测方法; ii）受二进制MAT的可逆性属性的启发，我们还将每个中间点与一个局部编码关联起来，这个局部编码允许我们反转AMAT，重建输入图像; iii）我们描述了一种聚类方案，它利用附加的尺度和外观信息将各个点分组到内侧分支，从而提供底层图像区域的形状分解。在我们的实验中，我们展示了Berkeley Medial AXes（BMAX500），基于BSDS500数据库的一个新的中轴数据集，以及SK506和WH-SYMMAX数据集的良好概括性。我们还测量BMAX500重建图像的质量，通过反演其计算的AMAT获得。我们的方法在三条基线方面提供了显着改善的重建质量，仅使用了10％的图像像素。我们的代码和注释可在此https网址获得。

##### URL
[https://arxiv.org/abs/1703.08628](https://arxiv.org/abs/1703.08628)

##### PDF
[https://arxiv.org/pdf/1703.08628](https://arxiv.org/pdf/1703.08628)

