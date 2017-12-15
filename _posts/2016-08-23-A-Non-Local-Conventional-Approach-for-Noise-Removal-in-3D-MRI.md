---
layout: post
title: "A Non-Local Conventional Approach for Noise Removal in 3D MRI"
date: 2016-08-23 15:58:29
categories: arXiv_CV
tags: arXiv_CV
author: Sona Morajab, Mehregan Mahdavi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a filtering approach for the 3D magnetic resonance imaging (MRI) assuming a Rician model for noise is addressed. Our denoising method is based on the Conventional Approach (CA) proposed to deal with the noise issue in the squared domain of the acquired magnitude MRI, where the noise distribution follows a Chi-square model rather than the Rician one. In the CA filtering method, the local samples around each voxel is used to estimate the unknown signal value. Intrinsically, such a method fails to achieve the best results where the underlying signal values have different statistical properties. On the contrary, our proposal takes advantage of the data redundancy and self-similarity properties of real MR images to improve the noise removal performance. In other words, in our approach, the statistical momentums of the given 3D MR volume are first calculated to explore the similar patches inside a defined search volume. Then, these patches are put together to obtain the noise-free value for each voxel under processing. The experimental results on the synthetic as well as the clinical MR data show our proposed method outperforms the other compared denoising filters.

##### Abstract (translated by Google)
在本文中，假设噪声为Rician模型的三维磁共振成像（MRI）的过滤方法被解决。我们的去噪方法是基于传统方法（CA）提出的，用于处理获取的幅度平方域的噪声问题，其中噪声分布遵循卡方模型而不是莱斯模型。在CA滤波方法中，使用每个体素周围的局部样本估计未知信号值。本质上，这种方法在底层信号值具有不同统计特性的情况下无法达到最佳效果。相反，我们的建议利用了真实MR图像的数据冗余和自相似性来改善噪声去除性能。换句话说，在我们的方法中，首先计算给定3D MR体积的统计动量，以探索定义的搜索体积内的类似的斑块。然后，将这些贴片放在一起以获得处理中的每个体素的无噪声值。综合和临床磁共振数据的实验结果表明，我们提出的方法胜过其他比较去噪滤波器。

##### URL
[https://arxiv.org/abs/1608.06558](https://arxiv.org/abs/1608.06558)

##### PDF
[https://arxiv.org/pdf/1608.06558](https://arxiv.org/pdf/1608.06558)

