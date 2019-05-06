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


##### URL
[https://arxiv.org/abs/1604.07060](https://arxiv.org/abs/1604.07060)

##### PDF
[https://arxiv.org/pdf/1604.07060](https://arxiv.org/pdf/1604.07060)

