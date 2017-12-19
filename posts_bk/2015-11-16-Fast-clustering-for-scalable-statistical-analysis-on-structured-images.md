---
layout: post
title: "Fast clustering for scalable statistical analysis on structured images"
date: 2015-11-16 10:26:18
categories: arXiv_CV
tags: arXiv_CV
author: Bertrand Thirion (PARIETAL), Andrés Hoyos-Idrobo (NEUROSPIN, PARIETAL), Jonas Kahn (LPP), Gael Varoquaux (NEUROSPIN, PARIETAL)
mathjax: true
---

* content
{:toc}

##### Abstract
The use of brain images as markers for diseases or behavioral differences is challenged by the small effects size and the ensuing lack of power, an issue that has incited researchers to rely more systematically on large cohorts. Coupled with resolution increases, this leads to very large datasets. A striking example in the case of brain imaging is that of the Human Connectome Project: 20 Terabytes of data and growing. The resulting data deluge poses severe challenges regarding the tractability of some processing steps (discriminant analysis, multivariate models) due to the memory demands posed by these data. In this work, we revisit dimension reduction approaches, such as random projections, with the aim of replacing costly function evaluations by cheaper ones while decreasing the memory requirements. Specifically, we investigate the use of alternate schemes, based on fast clustering, that are well suited for signals exhibiting a strong spatial structure, such as anatomical and functional brain images. Our contribution is twofold: i) we propose a linear-time clustering scheme that bypasses the percolation issues inherent in these algorithms and thus provides compressions nearly as good as traditional quadratic-complexity variance-minimizing clustering schemes, ii) we show that cluster-based compression can have the virtuous effect of removing high-frequency noise, actually improving subsequent estimations steps. As a consequence, the proposed approach yields very accurate models on several large-scale problems yet with impressive gains in computational efficiency, making it possible to analyze large datasets.

##### Abstract (translated by Google)
使用大脑图像作为疾病或行为差异的标志受到小尺寸效应和随之而来的缺乏力量的挑战，这个问题激发了研究人员更系统地依赖大群体。再加上分辨率增加，这导致非常大的数据集。大脑成像的一个显着例子就是人类连接组计划：20TB的数据和增长。由于这些数据造成的记忆需求，所导致的数据洪水对于一些处理步骤（判别分析，多变量模型）的易处理性提出了严峻的挑战。在这项工作中，我们重新审视降维方法，如随机预测，目的是用较便宜的功能评估代替昂贵的功能评估，同时减少内存需求。具体而言，我们调查了基于快速聚类的替代方案的使用，其非常适合于展现出强烈空间结构的信号，例如解剖和功能性脑图像。我们的贡献是双重的：i）我们提出了一种线性时间聚类方案，绕过了这些算法固有的渗透问题，因此提供的压缩几乎与传统的二次复杂度方差最小化聚类方案一样好，ii）我们展示了基于聚类压缩可以起到消除高频噪声的良性效果，实际上改善了后续的估计步骤。结果，所提出的方法在几个大规模问题上产生了非常准确的模型，但是在计算效率方面有显着的提高，使得可以分析大型数据集。

##### URL
[https://arxiv.org/abs/1511.04898](https://arxiv.org/abs/1511.04898)

##### PDF
[https://arxiv.org/pdf/1511.04898](https://arxiv.org/pdf/1511.04898)

