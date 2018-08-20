---
layout: post
title: "Medical Image Imputation from Image Collections"
date: 2018-08-17 02:46:33
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse
author: Adrian V. Dalca, Katherine L. Bouman, William T. Freeman, Natalia S. Rost, Mert R. Sabuncu, Polina Golland
mathjax: true
---

* content
{:toc}

##### Abstract
We present an algorithm for creating high resolution anatomically plausible images consistent with acquired clinical brain MRI scans with large inter-slice spacing. Although large data sets of clinical images contain a wealth of information, time constraints during acquisition result in sparse scans that fail to capture much of the anatomy. These characteristics often render computational analysis impractical as many image analysis algorithms tend to fail when applied to such images. Highly specialized algorithms that explicitly handle sparse slice spacing do not generalize well across problem domains. In contrast, we aim to enable application of existing algorithms that were originally developed for high resolution research scans to significantly undersampled scans. We introduce a generative model that captures fine-scale anatomical structure across subjects in clinical image collections and derive an algorithm for filling in the missing data in scans with large inter-slice spacing. Our experimental results demonstrate that the resulting method outperforms state-of-the-art upsampling super-resolution techniques, and promises to facilitate subsequent analysis not previously possible with scans of this quality. Our implementation is freely available at https://github.com/adalca/papago .

##### Abstract (translated by Google)
我们提出了一种算法，用于创建高分辨率的解剖学上合理的图像，与具有大的切片间间隔的获得的临床脑MRI扫描一致。尽管临床图像的大数据集包含大量信息，但是在采集期间的时间限制导致稀疏扫描未能捕获大部分解剖结构。这些特征经常使计算分析变得不切实际，因为许多图像分析算法在应用于这样的图像时往往会失败。明确处理稀疏切片间距的高度专业化算法不能在问题域中很好地概括。相比之下，我们的目标是将最初为高分辨率研究扫描开发的现有算法应用于显着欠采样的扫描。我们引入了一种生成模型，该模型捕获临床图像集合中受试者的精细尺度解剖结构，并导出一种算法，用于填充具有大的切片间间隔的扫描中的缺失数据。我们的实验结果表明，所得到的方法优于最先进的上采样超分辨率技术，并且有望通过扫描此质量来促进之前无法进行的后续分析。我们的实施可以在https://github.com/adalca/papago免费获得。

##### URL
[http://arxiv.org/abs/1808.05732](http://arxiv.org/abs/1808.05732)

##### PDF
[http://arxiv.org/pdf/1808.05732](http://arxiv.org/pdf/1808.05732)

