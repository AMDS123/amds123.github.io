---
layout: post
title: "Efficient Implementation of a Recognition System Using the Cortex Ventral Stream Model"
date: 2017-11-21 15:03:04
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization Recognition
author: Ahmad W. Bitar (Ahmad Wasfi Bitar), Mohammad M. Mansour, Ali Chehab
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, an efficient implementation for a recognition system based on the original HMAX model of the visual cortex is proposed. Various optimizations targeted to increase accuracy at the so-called layers S1, C1, and S2 of the HMAX model are proposed. At layer S1, all unimportant information such as illumination and expression variations are eliminated from the images. Each image is then convolved with 64 separable Gabor filters in the spatial domain. At layer C1, the minimum scales values are exploited to be embedded into the maximum ones using the additive embedding space. At layer S2, the prototypes are generated in a more efficient way using Partitioning Around Medoid (PAM) clustering algorithm. The impact of these optimizations in terms of accuracy and computational complexity was evaluated on the Caltech101 database, and compared with the baseline performance using support vector machine (SVM) and nearest neighbor (NN) classifiers. The results show that our model provides significant improvement in accuracy at the S1 layer by more than 10% where the computational complexity is also reduced. The accuracy is slightly increased for both approximations at the C1 and S2 layers.

##### Abstract (translated by Google)
本文提出了一种基于视觉皮层原始HMAX模型的识别系统的有效实现。提出了旨在提高HMAX模型的所谓的层S1，C1和S2的准确性的各种优化。在图层S1中，从图像中消除所有不重要的信息，例如照明和表情变化。然后，每个图像在空间域中与64个可分离的Gabor滤波器进行卷积。在C1层，利用加性嵌入空间将最小尺度值嵌入到最大尺度值中。在S2层，使用Partitioning Around Medoid（PAM）聚类算法以更高效的方式生成原型。在Caltech101数据库上评估这些优化在准确性和计算复杂性方面的影响，并与使用支持向量机（SVM）和最近邻（NN）分类器的基线性能进行比较。结果表明，我们的模型在计算复杂度也降低的情况下，在S1层的准确性提高了10％以上。对于C1和S2两层的近似值，精度略有提高。

##### URL
[https://arxiv.org/abs/1711.07827](https://arxiv.org/abs/1711.07827)

##### PDF
[https://arxiv.org/pdf/1711.07827](https://arxiv.org/pdf/1711.07827)

