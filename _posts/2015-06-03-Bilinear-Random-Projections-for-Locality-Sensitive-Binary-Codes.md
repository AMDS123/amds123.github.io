---
layout: post
title: "Bilinear Random Projections for Locality-Sensitive Binary Codes"
date: 2015-06-03 00:30:26
categories: arXiv_CV
tags: arXiv_CV Relation
author: Saehoon Kim, Seungjin Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Locality-sensitive hashing (LSH) is a popular data-independent indexing method for approximate similarity search, where random projections followed by quantization hash the points from the database so as to ensure that the probability of collision is much higher for objects that are close to each other than for those that are far apart. Most of high-dimensional visual descriptors for images exhibit a natural matrix structure. When visual descriptors are represented by high-dimensional feature vectors and long binary codes are assigned, a random projection matrix requires expensive complexities in both space and time. In this paper we analyze a bilinear random projection method where feature matrices are transformed to binary codes by two smaller random projection matrices. We base our theoretical analysis on extending Raginsky and Lazebnik's result where random Fourier features are composed with random binary quantizers to form locality sensitive binary codes. To this end, we answer the following two questions: (1) whether a bilinear random projection also yields similarity-preserving binary codes; (2) whether a bilinear random projection yields performance gain or loss, compared to a large linear projection. Regarding the first question, we present upper and lower bounds on the expected Hamming distance between binary codes produced by bilinear random projections. In regards to the second question, we analyze the upper and lower bounds on covariance between two bits of binary codes, showing that the correlation between two bits is small. Numerical experiments on MNIST and Flickr45K datasets confirm the validity of our method.

##### Abstract (translated by Google)
局部敏感散列（LSH）是近似相似搜索的一种流行的与数据无关的索引方法，其中随机投影和量化散列来自数据库的点，以确保碰撞的概率远高于接近于而不是那些相隔甚远的人。图像的大部分高维视觉描述符呈现出自然的矩阵结构。当视觉描述符由高维特征向量表示并且长二进制码被分配时，随机投影矩阵在空间和时间上都需要昂贵的复杂度。在本文中，我们分析了一个双线性随机投影方法，其中特征矩阵被两个较小的随机投影矩阵转换为二进制码。我们的理论分析基础是扩展Raginsky和Lazebnik的随机傅里叶特征与随机二进制量化器组成的结果，形成局部敏感的二进制编码。为此，我们回答以下两个问题：（1）双线性随机投影是否也产生了保留相似性的二进制码; （2）与大线性投影相比，双线性随机投影是否产生性能增益或损失。关于第一个问题，我们给出了由双线性随机投影产生的二进制码之间的预期汉明距离的上限和下限。关于第二个问题，我们分析两位二进制码之间协方差的上下限，表明两位之间的相关性很小。 MNIST和Flickr45K数据集上的数值实验证实了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1506.01092](https://arxiv.org/abs/1506.01092)

##### PDF
[https://arxiv.org/pdf/1506.01092](https://arxiv.org/pdf/1506.01092)

