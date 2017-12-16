---
layout: post
title: "Is Second-order Information Helpful for Large-scale Visual Recognition?"
date: 2017-07-31 11:54:19
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative Recognition
author: Peihua Li, Jiangtao Xie, Qilong Wang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
By stacking layers of convolution and nonlinearity, convolutional networks (ConvNets) effectively learn from low-level to high-level features and discriminative representations. Since the end goal of large-scale recognition is to delineate complex boundaries of thousands of classes, adequate exploration of feature distributions is important for realizing full potentials of ConvNets. However, state-of-the-art works concentrate only on deeper or wider architecture design, while rarely exploring feature statistics higher than first-order. We take a step towards addressing this problem. Our method consists in covariance pooling, instead of the most commonly used first-order pooling, of high-level convolutional features. The main challenges involved are robust covariance estimation given a small sample of large-dimensional features and usage of the manifold structure of covariance matrices. To address these challenges, we present a Matrix Power Normalized Covariance (MPN-COV) method. We develop forward and backward propagation formulas regarding the nonlinear matrix functions such that MPN-COV can be trained end-to-end. In addition, we analyze both qualitatively and quantitatively its advantage over the well-known Log-Euclidean metric. On the ImageNet 2012 validation set, by combining MPN-COV we achieve over 4%, 3% and 2.5% gains for AlexNet, VGG-M and VGG-16, respectively; integration of MPN-COV into 50-layer ResNet outperforms ResNet-101 and is comparable to ResNet-152. The source code will be available on the project page: this http URL

##### Abstract (translated by Google)
卷积网络（ConvNets）通过叠加卷积和非线性层次，有效地从低层次到高层次的特征和区分性表征中学习。由于大规模识别的最终目标是描绘数千个类别的复杂边界，因此充分发掘特征分布对于充分发挥ConvNets的潜力是非常重要的。然而，最先进的作品只专注于更深更广的建筑设计，而很少探索高于一阶的特征统计。我们朝着解决这个问题迈出了一步。我们的方法在于协方差池，而不是最常用的一阶池，高层次的卷积特征。所涉及的主要挑战是给定一个大维特征的小样本和协方差矩阵的流形结构的使用的鲁棒协方差估计。为了解决这些挑战，我们提出了矩阵功率归一化协方差（MPN-COV）方法。我们开发关于非线性矩阵函数的前向和后向传播公式，使得MPN-COV可以被端对端地训练。另外，我们从定性和定量两个方面分析了其优于Log-Euclidean度量的优势。在ImageNet 2012验证集中，通过结合MPN-COV，我们分别为AlexNet，VGG-M和VGG-16获得4％，3％和2.5％的收益;将MPN-COV整合到50层ResNet中的性能优于ResNet-101，与ResNet-152相当。源代码将在项目页面上提供：http URL

##### URL
[https://arxiv.org/abs/1703.08050](https://arxiv.org/abs/1703.08050)

##### PDF
[https://arxiv.org/pdf/1703.08050](https://arxiv.org/pdf/1703.08050)

