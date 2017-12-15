---
layout: post
title: "VRFP: On-the-fly Video Retrieval using Web Images and Fast Fisher Vector Products"
date: 2017-04-10 17:28:16
categories: arXiv_CV
tags: arXiv_CV
author: Xintong Han, Bharat Singh, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
VRFP is a real-time video retrieval framework based on short text input queries, which obtains weakly labeled training images from the web after the query is known. The retrieved web images representing the query and each database video are treated as unordered collections of images, and each collection is represented using a single Fisher Vector built on CNN features. Our experiments show that a Fisher Vector is robust to noise present in web images and compares favorably in terms of accuracy to other standard representations. While a Fisher Vector can be constructed efficiently for a new query, matching against the test set is slow due to its high dimensionality. To perform matching in real-time, we present a lossless algorithm that accelerates the inner product computation between high dimensional Fisher Vectors. We prove that the expected number of multiplications required decreases quadratically with the sparsity of Fisher Vectors. We are not only able to construct and apply query models in real-time, but with the help of a simple re-ranking scheme, we also outperform state-of-the-art automatic retrieval methods by a significant margin on TRECVID MED13 (3.5%), MED14 (1.3%) and CCV datasets (5.2%). We also provide a direct comparison on standard datasets between two different paradigms for automatic video retrieval - zero-shot learning and on-the-fly retrieval.

##### Abstract (translated by Google)
VRFP是一种基于短文本输入查询的实时视频检索框架，在知道查询后从网上获取弱标识的训练图像。表示查询和每个数据库视频的检索的网页图像被视为图像的无序集合，并且每个集合使用建立在CNN特征上的单个Fisher Vector来表示。我们的实验表明，Fisher矢量对于网页图像中存在的噪声具有鲁棒性，并且与其他标准表示方法相比，在精度方面相当有利。虽然费舍尔向量可以有效地构建一个新的查询，但由于维数高，匹配测试集的速度很慢。为了进行实时匹配，我们提出了一个无损算法，加快了高维Fisher向量之间的内积计算。我们用Fisher矢量的稀疏性来证明所需的乘法运算的次数会减少。我们不仅能够实时构建和应用查询模型，而且借助简单的重新排序方案，我们在TRECVID MED13（3.5版本）上的性能也优于最先进的自动检索方法。 ％），MED14（1.3％）和CCV数据集（5.2％）。我们还提供了两种不同的自动视频检索模式的标准数据集的直接比较 - 零点学习和动态检索。

##### URL
[https://arxiv.org/abs/1512.03384](https://arxiv.org/abs/1512.03384)

##### PDF
[https://arxiv.org/pdf/1512.03384](https://arxiv.org/pdf/1512.03384)

