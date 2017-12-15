---
layout: post
title: "Binary Codes for Tagging X-Ray Images via Deep De-Noising Autoencoders"
date: 2016-04-24 17:44:30
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Regularization Relation
author: Antonio Sze-To, Hamid R. Tizhoosh, Andrew K.C. Wong
mathjax: true
---

* content
{:toc}

##### Abstract
A Content-Based Image Retrieval (CBIR) system which identifies similar medical images based on a query image can assist clinicians for more accurate diagnosis. The recent CBIR research trend favors the construction and use of binary codes to represent images. Deep architectures could learn the non-linear relationship among image pixels adaptively, allowing the automatic learning of high-level features from raw pixels. However, most of them require class labels, which are expensive to obtain, particularly for medical images. The methods which do not need class labels utilize a deep autoencoder for binary hashing, but the code construction involves a specific training algorithm and an ad-hoc regularization technique. In this study, we explored using a deep de-noising autoencoder (DDA), with a new unsupervised training scheme using only backpropagation and dropout, to hash images into binary codes. We conducted experiments on more than 14,000 x-ray images. By using class labels only for evaluating the retrieval results, we constructed a 16-bit DDA and a 512-bit DDA independently. Comparing to other unsupervised methods, we succeeded to obtain the lowest total error by using the 512-bit codes for retrieval via exhaustive search, and speed up 9.27 times with the use of the 16-bit codes while keeping a comparable total error. We found that our new training scheme could reduce the total retrieval error significantly by 21.9%. To further boost the image retrieval performance, we developed Radon Autoencoder Barcode (RABC) which are learned from the Radon projections of images using a de-noising autoencoder. Experimental results demonstrated its superior performance in retrieval when it was combined with DDA binary codes.

##### Abstract (translated by Google)
基于查询图像识别相似医学图像的基于内容的图像检索（CBIR）系统可以帮助临床医生进行更准确的诊断。最近的CBIR研究趋势有利于构建和使用二进制代码来表示图像。深度架构可以自适应地学习图像像素之间的非线性关系，允许从原始像素自动学习高级特征。然而，其中大多数都需要班级标签，这些标签的价格昂贵，特别是对于医学图像。不需要类标签的方法利用深度自动编码器进行二进制散列，但代码构造涉及特定的训练算法和特别的正则化技术。在这项研究中，我们探索使用深度去噪自动编码器（DDA），一个新的无监督训练方案只使用反向传播和丢失，哈希图像二进制代码。我们对超过14,000张X射线图像进行了实验。通过仅使用类标签来评估检索结果，我们独立地构建了16位DDA和512位DDA。与其他无监督方法相比，我们成功地通过使用512位的代码通过穷举搜索获得最低的总误差，并且在保持相当的总误差的同时使用16位代码加速了9.27倍。我们发现，我们的新的训练方案可以显着减少21.9％的总检索错误。为了进一步提高图像检索性能，我们开发了氡自动编码器条码（RABC），这是从图像的氡投影学习使用去噪自动编码器。实验结果表明，在与DDA二进制编码相结合时，其检索性能优越。

##### URL
[https://arxiv.org/abs/1604.07060](https://arxiv.org/abs/1604.07060)

##### PDF
[https://arxiv.org/pdf/1604.07060](https://arxiv.org/pdf/1604.07060)

