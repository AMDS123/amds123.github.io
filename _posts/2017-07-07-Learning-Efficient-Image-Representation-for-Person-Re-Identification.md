---
layout: post
title: "Learning Efficient Image Representation for Person Re-Identification"
date: 2017-07-07 18:05:48
categories: arXiv_CV
tags: arXiv_CV Image_Caption Re-identification Person_Re-identification
author: Yang Yang, Shengcai Liao, Zhen Lei, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Color names based image representation is successfully used in person re-identification, due to the advantages of being compact, intuitively understandable as well as being robust to photometric variance. However, there exists the diversity between underlying distribution of color names' RGB values and that of image pixels' RGB values, which may lead to inaccuracy when directly comparing them in Euclidean space. In this paper, we propose a new method named soft Gaussian mapping (SGM) to address this problem. We model the discrepancies between color names and pixels using a Gaussian and utilize the inverse of covariance matrix to bridge the gap between them. Based on SGM, an image could be converted to several soft Gaussian maps. In each soft Gaussian map, we further seek to establish stable and robust descriptors within a local region through a max pooling operation. Then, a robust image representation based on color names is obtained by concatenating the statistical descriptors in each stripe. When labeled data are available, one discriminative subspace projection matrix is learned to build efficient representations of an image via cross-view coupling learning. Experiments on the public datasets - VIPeR, PRID450S and CUHK03, demonstrate the effectiveness of our method.

##### Abstract (translated by Google)
基于颜色名称的图像表示被成功地用于个人重新识别，由于紧凑，直观易懂以及对光度变化的稳健性的优点。然而，颜色名称的RGB值的底层分布与图像像素的RGB值的分布之间存在着多样性，在欧几里得空间直接比较时可能会导致不准确。在本文中，我们提出了一种新的软高斯映射（SGM）方法来解决这个问题。我们使用高斯来对颜色名称和像素之间的差异进行建模，并利用协方差矩阵的逆来弥补它们之间的差距。基于SGM，图像可以被转换成几个软高斯地图。在每个软高斯图中，我们进一步试图通过最大池操作在局部区域内建立稳定和鲁棒的描述符。然后，通过连接每个条带中的统计描述符来获得基于颜色名称的可靠图像表示。当有标记的数据可用时，学习一个判别性子空间投影矩阵，以通过交叉视角耦合学习建立图像的高效表示。公共数据集上的实验 -  VIPeR，PRID450S和CUHK03证明了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1707.02319](https://arxiv.org/abs/1707.02319)

##### PDF
[https://arxiv.org/pdf/1707.02319](https://arxiv.org/pdf/1707.02319)

