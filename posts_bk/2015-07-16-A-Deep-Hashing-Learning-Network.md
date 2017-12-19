---
layout: post
title: "A Deep Hashing Learning Network"
date: 2015-07-16 02:57:59
categories: arXiv_CV
tags: arXiv_CV CNN
author: Guoqiang Zhong, Pan Yang, Sijiang Wang, Junyu Dong
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing-based methods seek compact and efficient binary codes that preserve the neighborhood structure in the original data space. For most existing hashing methods, an image is first encoded as a vector of hand-crafted visual feature, followed by a hash projection and quantization step to get the compact binary vector. Most of the hand-crafted features just encode the low-level information of the input, the feature may not preserve the semantic similarities of images pairs. Meanwhile, the hashing function learning process is independent with the feature representation, so the feature may not be optimal for the hashing projection. In this paper, we propose a supervised hashing method based on a well designed deep convolutional neural network, which tries to learn hashing code and compact representations of data simultaneously. The proposed model learn the binary codes by adding a compact sigmoid layer before the loss layer. Experiments on several image data sets show that the proposed model outperforms other state-of-the-art methods.

##### Abstract (translated by Google)
基于散列的方法寻求紧凑和有效的二进制代码，以保留原始数据空间中的邻域结构。对于大多数现有的哈希方法，首先将图像编码为手工制作的视觉特征的向量，然后进行哈希投影和量化步骤以获得紧凑的二进制向量。大部分手工特征只是对输入的低级信息进行编码，而不能保留图像对的语义相似性。同时，哈希函数学习过程与特征表示无关，因此哈希投影特征可能不是最优的。在本文中，我们提出了一种基于精心设计的深度卷积神经网络的监督哈希方法，试图同时学习哈希码和紧凑的数据表示。所提出的模型通过在损失层之前添加紧凑S形图层来学习二进制代码。在几个图像数据集上的实验表明，所提出的模型优于其他最先进的方法。

##### URL
[https://arxiv.org/abs/1507.04437](https://arxiv.org/abs/1507.04437)

##### PDF
[https://arxiv.org/pdf/1507.04437](https://arxiv.org/pdf/1507.04437)

