---
layout: post
title: "Basic Thresholding Classification"
date: 2017-12-08 18:46:11
categories: arXiv_CV
tags: arXiv_CV Face Image_Classification Classification
author: Mehmet Altan Toks&#xf6;z
mathjax: true
---

* content
{:toc}

##### Abstract
In this thesis, we propose a light-weight sparsity-based algorithm, basic thresholding classifier (BTC), for classification applications (such as face identification, hyper-spectral image classification, etc.) which is capable of identifying test samples extremely rapidly and performing high classification accuracy. Originally BTC is a linear classifier which works based on the assumption that the samples of the classes of a given dataset are linearly separable. However, in practice those samples may not be linearly separable. In this context, we also propose another algorithm namely kernel basic thresholding classifier (KBTC) which is a non-linear kernel version of the BTC algorithm. KBTC can achieve promising results especially when the given samples are linearly non-separable. For both proposals, we introduce sufficient identification conditions (SICs) under which BTC and KBTC can identify any test sample in the range space of a given dictionary. By using SICs, we develop parameter estimation procedures which do not require any cross validation. Both BTC and KBTC algorithms provide efficient classifier fusion schemes in which individual classifier outputs are combined to produce better classification results. For instance, for the application of face identification, this is done by combining the residuals having different random projectors. For spatial applications such as hyper-spectral image classification, the fusion is carried out by incorporating the spatial information, in which the output residual maps are filtered using a smoothing filter. Numerical results on publicly available face and hyper-spectral datasets show that our proposal outperforms well-known support vector machines (SVM)-based techniques, multinomial logistic regression (MLR)-based methods, and sparsity-based approaches like $l_1$-minimization and simultaneous orthogonal matching pursuit (SOMP).

##### Abstract (translated by Google)
本文针对能够快速识别测试样本的分类应用（如人脸识别，高光谱图像分类等），提出一种基于轻量稀疏的算法 - 基本阈值分类器（BTC）执行高分类准确性。最初BTC是一个线性分类器，它基于给定数据集的类的样本可线性分离的假设工作。但是，实际上这些样本可能不是线性可分的。在这种情况下，我们还提出了另一种算法，即核心基本阈值分类器（KBTC），它是BTC算法的一个非线性内核版本。 KBTC可以取得有希望的结果，特别是当给定的样品是线性不可分离的。对于这两个建议，我们引入足够的识别条件（SIC），BTC和KBTC可以在给定的字典范围空间中识别任何测试样本。通过使用SIC，我们开发了不需要交叉验证的参数估计程序。 BTC和KBTC算法都提供了有效的分类器融合方案，其中单独的分类器输出被组合以产生更好的分类结果。例如，对于人脸识别的应用，这是通过组合具有不同随机投影仪的残差来完成的。对于诸如高光谱图像分类的空间应用，通过合并空间信息来执行融合，其中使用平滑滤波器对输出残差图进行滤波。在公开可用的人脸和高光谱数据集上的数值结果表明，我们的建议优于众所周知的基于支持向量机（SVM）的技术，基于多项目逻辑回归（MLR）的方法和基于稀疏性的方法，如$ l_1 $最小化和同时正交匹配追踪（SOMP）。

##### URL
[http://arxiv.org/abs/1712.03217](http://arxiv.org/abs/1712.03217)

##### PDF
[http://arxiv.org/pdf/1712.03217](http://arxiv.org/pdf/1712.03217)

