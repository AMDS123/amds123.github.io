---
layout: post
title: "Local Multi-Grouped Binary Descriptor with Ring-based Pooling Configuration and Optimization"
date: 2015-09-22 11:56:21
categories: arXiv_CV
tags: arXiv_CV Sparse Attention Optimization Relation
author: Yongqiang Gao, Weilin Huang, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Local binary descriptors are attracting increasingly attention due to their great advantages in computational speed, which are able to achieve real-time performance in numerous image/vision applications. Various methods have been proposed to learn data-dependent binary descriptors. However, most existing binary descriptors aim overly at computational simplicity at the expense of significant information loss which causes ambiguity in similarity measure using Hamming distance. In this paper, by considering multiple features might share complementary information, we present a novel local binary descriptor, referred as Ring-based Multi-Grouped Descriptor (RMGD), to successfully bridge the performance gap between current binary and floated-point descriptors. Our contributions are two-fold. Firstly, we introduce a new pooling configuration based on spatial ring-region sampling, allowing for involving binary tests on the full set of pairwise regions with different shapes, scales and distances. This leads to a more meaningful description than existing methods which normally apply a limited set of pooling configurations. Then, an extended Adaboost is proposed for efficient bit selection by emphasizing high variance and low correlation, achieving a highly compact representation. Secondly, the RMGD is computed from multiple image properties where binary strings are extracted. We cast multi-grouped features integration as rankSVM or sparse SVM learning problem, so that different features can compensate strongly for each other, which is the key to discriminativeness and robustness. The performance of RMGD was evaluated on a number of publicly available benchmarks, where the RMGD outperforms the state-of-the-art binary descriptors significantly.

##### Abstract (translated by Google)
局部二进制描述符由于它们在计算速度上的巨大优势而受到越来越多的关注，它们能够在许多图像/视觉应用中实现实时性能。已经提出了各种方法来学习数据相关二进制描述符。然而，大多数现有的二进制描述符过于简单地以计算简单为代价，其代价是显着的信息损失，这导致使用汉明距离的相似性度量的模糊性。在本文中，通过考虑多个特征可能共享互补信息，我们提出了一种新颖的局部二进制描述符（称为基于环的多分组描述符（RMGD）），以成功地弥补当前二进制和浮点描述符之间的性能差距。我们的贡献是双重的。首先，我们引入一种基于空间环形采样的新的池化配置，允许对具有不同形状，尺度和距离的成对区域进行二元测试。这比通常应用有限的池化配置的现有方法导致更有意义的描述。然后，通过强调高方差和低相关性，提出了一种扩展Adaboost来实现高效位选择，实现了高度紧凑的表示。其次，从提取二进制字符串的多个图像属性计算RMGD。我们将多分类特征集成为秩SVM或稀疏SVM学习问题，使得不同的特征可以相互强烈地进行补偿，这是区分性和鲁棒性的关键。 RMGD的性能在许多公开可用的基准上进行了评估，其中RMGD显着优于最先进的二进制描述符。

##### URL
[https://arxiv.org/abs/1509.06557](https://arxiv.org/abs/1509.06557)

##### PDF
[https://arxiv.org/pdf/1509.06557](https://arxiv.org/pdf/1509.06557)

