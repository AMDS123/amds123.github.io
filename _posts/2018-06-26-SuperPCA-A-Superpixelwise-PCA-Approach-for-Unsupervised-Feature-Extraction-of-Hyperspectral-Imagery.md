---
layout: post
title: "SuperPCA: A Superpixelwise PCA Approach for Unsupervised Feature Extraction of Hyperspectral Imagery"
date: 2018-06-26 06:38:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Junjun Jiang, Jiayi Ma, Chen Chen, Zhongyuan Wang, Zhihua Cai, Lizhe Wang
mathjax: true
---

* content
{:toc}

##### Abstract
As an unsupervised dimensionality reduction method, principal component analysis (PCA) has been widely considered as an efficient and effective preprocessing step for hyperspectral image (HSI) processing and analysis tasks. It takes each band as a whole and globally extracts the most representative bands. However, different homogeneous regions correspond to different objects, whose spectral features are diverse. It is obviously inappropriate to carry out dimensionality reduction through a unified projection for an entire HSI. In this paper, a simple but very effective superpixelwise PCA approach, called SuperPCA, is proposed to learn the intrinsic low-dimensional features of HSIs. In contrast to classical PCA models, SuperPCA has four main properties. (1) Unlike the traditional PCA method based on a whole image, SuperPCA takes into account the diversity in different homogeneous regions, that is, different regions should have different projections. (2) Most of the conventional feature extraction models cannot directly use the spatial information of HSIs, while SuperPCA is able to incorporate the spatial context information into the unsupervised dimensionality reduction by superpixel segmentation. (3) Since the regions obtained by superpixel segmentation have homogeneity, SuperPCA can extract potential low-dimensional features even under noise. (4) Although SuperPCA is an unsupervised method, it can achieve competitive performance when compared with supervised approaches. The resulting features are discriminative, compact, and noise resistant, leading to improved HSI classification performance. Experiments on three public datasets demonstrate that the SuperPCA model significantly outperforms the conventional PCA based dimensionality reduction baselines for HSI classification. The Matlab source code is available at https://github.com/junjun-jiang/SuperPCA.

##### Abstract (translated by Google)
作为一种无监督降维方法，主成分分析（PCA）已被广泛认为是高光谱图像（HSI）处理和分析任务的高效和有效的预处理步骤。它将每个乐队作为一个整体，并在全球范围内提取最具代表性的乐队。然而，不同的同质区域对应于不同的物体，其光谱特征是多样的。通过对整个恒指进行统一预测来降低维度显然是不合适的。在本文中，提出了一种简单但非常有效的超像素PCA方法SuperPCA，用于了解HSI的内在低维特征。与传统的PCA模型相反，SuperPCA有四个主要特性。 （1）与基于整幅图像的传统PCA方法不同，SuperPCA考虑了不同均匀区域的多样性，即不同地区应该有不同的预测。 （2）大多数传统特征提取模型不能直接使用HSI的空间信息，而SuperPCA能够将空间上下文信息纳入超像素分割的无监督降维。 （3）由于超像素分割得到的区域具有均匀性，SuperPCA即使在噪声下也可以提取潜在的低维特征。 （4）虽然SuperPCA是一种无监督方法，但与监督方法相比，它可以获得有竞争力的表现。由此产生的特性具有区分性，紧凑性和抗噪声性，从而提高了HSI分类性能。三个公共数据集上的实验表明，SuperPCA模型显着优于常规基于PCA的HSI分类降维基线。 Matlab源代码可在https://github.com/junjun-jiang/SuperPCA上找到。

##### URL
[http://arxiv.org/abs/1806.09807](http://arxiv.org/abs/1806.09807)

##### PDF
[http://arxiv.org/pdf/1806.09807](http://arxiv.org/pdf/1806.09807)

