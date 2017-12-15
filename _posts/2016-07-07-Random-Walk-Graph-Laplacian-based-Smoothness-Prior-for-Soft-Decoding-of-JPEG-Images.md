---
layout: post
title: "Random Walk Graph Laplacian based Smoothness Prior for Soft Decoding of JPEG Images"
date: 2016-07-07 07:31:22
categories: arXiv_CV
tags: arXiv_CV
author: Xianming Liu, Gene Cheung, Xiaolin Wu, Debin Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Given the prevalence of JPEG compressed images, optimizing image reconstruction from the compressed format remains an important problem. Instead of simply reconstructing a pixel block from the centers of indexed DCT coefficient quantization bins (hard decoding), soft decoding reconstructs a block by selecting appropriate coefficient values within the indexed bins with the help of signal priors. The challenge thus lies in how to define suitable priors and apply them effectively. In this paper, we combine three image priors---Laplacian prior for DCT coefficients, sparsity prior and graph-signal smoothness prior for image patches---to construct an efficient JPEG soft decoding algorithm. Specifically, we first use the Laplacian prior to compute a minimum mean square error (MMSE) initial solution for each code block. Next, we show that while the sparsity prior can reduce block artifacts, limiting the size of the over-complete dictionary (to lower computation) would lead to poor recovery of high DCT frequencies. To alleviate this problem, we design a new graph-signal smoothness prior (desired signal has mainly low graph frequencies) based on the left eigenvectors of the random walk graph Laplacian matrix (LERaG). Compared to previous graph-signal smoothness priors, LERaG has desirable image filtering properties with low computation overhead. We demonstrate how LERaG can facilitate recovery of high DCT frequencies of a piecewise smooth (PWS) signal via an interpretation of low graph frequency components as relaxed solutions to normalized cut in spectral clustering. Finally, we construct a soft decoding algorithm using the three signal priors with appropriate prior weights. Experimental results show that our proposal outperforms state-of-the-art soft decoding algorithms in both objective and subjective evaluations noticeably.

##### Abstract (translated by Google)
鉴于JPEG压缩图像的流行，从压缩格式优化图像重建仍然是一个重要问题。软解码不是简单地从索引DCT系数量化区间（硬解码）的中心重构像素块，而是借助于信号先验在索引仓内选择适当的系数值来重构块。因此，挑战在于如何定义合适的先验并有效地应用。在本文中，我们结合三个图像先验 - 拉普拉斯先验DCT系数，稀疏先验和图像信号平滑之前的图像补丁---构造一个有效的JPEG软解码算法。具体来说，我们首先使用拉普拉斯算子计算每个代码块的最小均方误差（MMSE）初始解。接下来，我们展示了虽然先验稀疏可以减少块伪影，但是限制过度完整字典的大小（以降低计算）将导致高DCT频率的恢复较差。为了缓解这个问题，我们基于随机游走图拉普拉斯矩阵（LERaG）的左特征向量设计了一个新的图信号平滑先验（期望信号主要具有低图频率）。与以前的图形信号平滑度先验相比，LERaG具有理想的图像滤波特性，计算开销小。我们演示LERaG如何通过将低图频率分量解释为归一化切割谱聚类的松散解决方案来帮助恢复分段平滑（PWS）信号的高DCT频率。最后，我们使用三个具有适当的先验权重的先验信号构造一个软解码算法。实验结果表明，我们的建议在客观和主观评价方面明显优于最新的软解码算法。

##### URL
[https://arxiv.org/abs/1607.01895](https://arxiv.org/abs/1607.01895)

##### PDF
[https://arxiv.org/pdf/1607.01895](https://arxiv.org/pdf/1607.01895)

