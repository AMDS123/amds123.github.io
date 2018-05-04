---
layout: post
title: "Deep Co-attention based Comparators For Relative Representation Learning in Person Re-identification"
date: 2018-04-30 02:35:46
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification Embedding Represenation_Learning
author: Lin Wu, Yang Wang, Junbin Gao, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-ID) requires rapid, flexible yet discriminant representations to quickly generalize to unseen observations on-the-fly and recognize the same identity across disjoint camera views. Recent effective methods are developed in a pair-wise similarity learning system to detect a fixed set of features from distinct regions which are mapped to their vector embeddings for the distance measuring. However, the most relevant and crucial parts of each image are detected independently without referring to the dependency conditioned on one and another. Also, these region based methods rely on spatial manipulation to position the local features in comparable similarity measuring. To combat these limitations, in this paper we introduce the Deep Co-attention based Comparators (DCCs) that fuse the co-dependent representations of the paired images so as to focus on the relevant parts of both images and produce their \textit{relative representations}. Given a pair of pedestrian images to be compared, the proposed model mimics the foveation of human eyes to detect distinct regions concurrent on both images, namely co-dependent features, and alternatively attend to relevant regions to fuse them into the similarity learning. Our comparator is capable of producing dynamic representations relative to a particular sample every time, and thus well-suited to the case of re-identifying pedestrians on-the-fly. We perform extensive experiments to provide the insights and demonstrate the effectiveness of the proposed DCCs in person re-ID. Moreover, our approach has achieved the state-of-the-art performance on three benchmark data sets: DukeMTMC-reID \cite{DukeMTMC}, CUHK03 \cite{FPNN}, and Market-1501 \cite{Market1501}.

##### Abstract (translated by Google)
人员重新识别（重新识别）需要快速，灵活但具有判别力的表示，以快速推广到不可见的观察，并在不相交的摄像机视图中识别相同的身份。在成对相似学习系统中开发了最近有效的方法，以从不同区域检测固定的一组特征，所述不同区域被映射到它们的用于距离测量的矢量嵌入。然而，每个图像中最相关和最关键的部分是独立检测的，而不涉及依赖于一个和另一个的依赖关系。而且，这些基于区域的方法依赖于空间操作来将局部特征定位在可比较的相似性测量中。为了克服这些局限性，在本文中，我们介绍基于深度共同关注的比较器（DCC），它将成对图像的相关表示融合在一起，以聚焦在两幅图像的相关部分并生成它们的\ textit {相对表示}。给定一对待比较的行人图像，所提出的模型模拟人眼的发育，以检测两幅图像上并行的不同区域，即共依赖特征，或者考虑相关区域以将它们融合到相似性学习中。我们的比较器每次都能够生成相对于特定样本的动态表示，因此非常适合于在行进中重新识别行人的情况。我们进行大量实验以提供见解并证明拟议的DCC在个人身份识别中的有效性。此外，我们的方法已经在三个基准数据集（DukeMTMC-reID \ cite {DukeMTMC}，CUHK03 \ cite {FPNN}和Market-1501 \ cite {Market1501}）上实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1804.11027](https://arxiv.org/abs/1804.11027)

##### PDF
[https://arxiv.org/pdf/1804.11027](https://arxiv.org/pdf/1804.11027)

