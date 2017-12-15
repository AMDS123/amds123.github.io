---
layout: post
title: "Autoencoding the Retrieval Relevance of Medical Images"
date: 2015-07-05 18:40:14
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Classification
author: Zehra Camlica, H.R. Tizhoosh, Farzad Khalvati
mathjax: true
---

* content
{:toc}

##### Abstract
Content-based image retrieval (CBIR) of medical images is a crucial task that can contribute to a more reliable diagnosis if applied to big data. Recent advances in feature extraction and classification have enormously improved CBIR results for digital images. However, considering the increasing accessibility of big data in medical imaging, we are still in need of reducing both memory requirements and computational expenses of image retrieval systems. This work proposes to exclude the features of image blocks that exhibit a low encoding error when learned by a $n/p/n$ autoencoder ($p\!<\!n$). We examine the histogram of autoendcoding errors of image blocks for each image class to facilitate the decision which image regions, or roughly what percentage of an image perhaps, shall be declared relevant for the retrieval task. This leads to reduction of feature dimensionality and speeds up the retrieval process. To validate the proposed scheme, we employ local binary patterns (LBP) and support vector machines (SVM) which are both well-established approaches in CBIR research community. As well, we use IRMA dataset with 14,410 x-ray images as test data. The results show that the dimensionality of annotated feature vectors can be reduced by up to 50% resulting in speedups greater than 27% at expense of less than 1% decrease in the accuracy of retrieval when validating the precision and recall of the top 20 hits.

##### Abstract (translated by Google)
医学图像的基于内容的图像检索（CBIR）是一项重要的任务，如果应用于大数据，可以提供更可靠的诊断。特征提取和分类方面的最新进展极大地提高了数字图像的CBIR结果。然而，考虑到大数据在医学成像中的可达性增加，我们仍然需要降低图像检索系统的存储器需求和计算开销。这项工作提出，通过$ n / p / n $ autoencoder（$ p \！<\！n $）学习时，排除表现出低编码错误的图像块的特征。我们检查每个图像类别的图像块的自动编码错误的直方图，以便于确定哪个图像区域，或者大概多少百分比的图像应该被宣布与检索任务相关。这导致了特征维度的降低，并加速了检索过程。为了验证所提出的方案，我们采用局部二进制模式（LBP）和支持向量机（SVM），这两种模式在CBIR研究领域都是非常成熟的方法。同样，我们使用具有14,410个X射线图像的IRMA数据集作为测试数据。结果表明，在验证前20个匹配的精确度和回忆率时，注释特征向量的维数可以减少多达50％，导致加速比大于27％，而检索精度降低不到1％。

##### URL
[https://arxiv.org/abs/1507.01251](https://arxiv.org/abs/1507.01251)

##### PDF
[https://arxiv.org/pdf/1507.01251](https://arxiv.org/pdf/1507.01251)

