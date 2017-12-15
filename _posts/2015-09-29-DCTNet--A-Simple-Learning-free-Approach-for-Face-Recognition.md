---
layout: post
title: "DCTNet : A Simple Learning-free Approach for Face Recognition"
date: 2015-09-29 11:38:10
categories: arXiv_CV
tags: arXiv_CV Face Image_Classification Classification Deep_Learning Recognition Face_Recognition
author: Cong Jie Ng, Andrew Beng Jin Teoh
mathjax: true
---

* content
{:toc}

##### Abstract
PCANet was proposed as a lightweight deep learning network that mainly leverages Principal Component Analysis (PCA) to learn multistage filter banks followed by binarization and block-wise histograming. PCANet was shown worked surprisingly well in various image classification tasks. However, PCANet is data-dependence hence inflexible. In this paper, we proposed a data-independence network, dubbed DCTNet for face recognition in which we adopt Discrete Cosine Transform (DCT) as filter banks in place of PCA. This is motivated by the fact that 2D DCT basis is indeed a good approximation for high ranked eigenvectors of PCA. Both 2D DCT and PCA resemble a kind of modulated sine-wave patterns, which can be perceived as a bandpass filter bank. DCTNet is free from learning as 2D DCT bases can be computed in advance. Besides that, we also proposed an effective method to regulate the block-wise histogram feature vector of DCTNet for robustness. It is shown to provide surprising performance boost when the probe image is considerably different in appearance from the gallery image. We evaluate the performance of DCTNet extensively on a number of benchmark face databases and being able to achieve on par with or often better accuracy performance than PCANet.

##### Abstract (translated by Google)
PCANet被认为是一个轻量级的深度学习网络，主要利用主成分分析（PCA）学习多级滤波器组，然后进行二值化和逐块直方图。 PCANet在各种图像分类任务中显示出令人惊讶的效果。但是，PCANet是数据依赖性因此不灵活。在本文中，我们提出了一个数据独立网络，称为DCTNet用于人脸识别，我们采用离散余弦变换（DCT）作为滤波器组代替PCA。这是由二维DCT基础对于PCA的高排序特征向量确实是一个很好的近似的事实所驱动的。二维DCT和PCA都类似于一种调制正弦波模式，可以看作是一个带通滤波器组。 DCTNet是免费的，因为二维DCT基地可以提前计算。除此之外，我们还提出了一种有效的方法来调整DCTNet的分块直方图特征向量的鲁棒性。当探头图像与图库图像的外观明显不同时，显示出令人惊讶的性能提升。我们在许多基准面数据库上广泛评估DCTNet的性能，并且能够达到与PCANet相比甚至更好的精度性能。

##### URL
[https://arxiv.org/abs/1507.02049](https://arxiv.org/abs/1507.02049)

##### PDF
[https://arxiv.org/pdf/1507.02049](https://arxiv.org/pdf/1507.02049)

