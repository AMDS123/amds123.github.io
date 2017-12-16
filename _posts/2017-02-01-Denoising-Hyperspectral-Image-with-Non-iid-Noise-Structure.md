---
layout: post
title: "Denoising Hyperspectral Image with Non-i.i.d. Noise Structure"
date: 2017-02-01 00:52:01
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention
author: Yang Chen, Xiangyong Cao, Qian Zhao, Deyu Meng, Zongben Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral image (HSI) denoising has been attracting much research attention in remote sensing area due to its importance in improving the HSI qualities. The existing HSI denoising methods mainly focus on specific spectral and spatial prior knowledge in HSIs, and share a common underlying assumption that the embedded noise in HSI is independent and identically distributed (i.i.d.). In real scenarios, however, the noise existed in a natural HSI is always with much more complicated non-i.i.d. statistical structures and the under-estimation to this noise complexity often tends to evidently degenerate the robustness of current methods. To alleviate this issue, this paper attempts the first effort to model the HSI noise using a non-i.i.d. mixture of Gaussians (NMoG) noise assumption, which is finely in accordance with the noise characteristics possessed by a natural HSI and thus is capable of adapting various noise shapes encountered in real applications. Then we integrate such noise modeling strategy into the low-rank matrix factorization (LRMF) model and propose a NMoG-LRMF model in the Bayesian framework. A variational Bayes algorithm is designed to infer the posterior of the proposed model. All involved parameters can be recursively updated in closed-form. Compared with the current techniques, the proposed method performs more robust beyond the state-of-the-arts, as substantiated by our experiments implemented on synthetic and real noisy HSIs.

##### Abstract (translated by Google)
高光谱图像（HSI）去噪技术在提高HSI质量方面的重要性，在遥感领域引起了越来越多的研究重视。现有的HSI去噪方法主要集中在HSI特有的频谱空间先验知识上，并且共享HSI中嵌入噪声是独立分布均匀分布（i.i.d.）的基本假设。然而，在实际情况下，自然恒指中存在的噪声总是比非i.i.d复杂得多。统计结构和对这种噪声复杂性的低估通常倾向于显着地退化当前方法的鲁棒性。为了缓解这个问题，本文首先尝试使用非i.i.d来模拟HSI噪声。高斯混合（NMoG）噪声假设，它很好地符合天然HSI所具有的噪声特性，因此能够适应实际应用中遇到的各种噪声形状。然后将这种噪声建模策略融入低阶矩阵分解（LRMF）模型，并在贝叶斯框架下提出NMoG-LRMF模型。变分贝叶斯算法被设计来推断所提出的模型的后验。所有涉及的参数都可以以封闭的形式递归更新。与当前的技术相比，所提出的方法在超越现有技术的情况下执行更强大，正如我们在合成和真实噪声HSI上实施的实验所证实的。

##### URL
[https://arxiv.org/abs/1702.00098](https://arxiv.org/abs/1702.00098)

##### PDF
[https://arxiv.org/pdf/1702.00098](https://arxiv.org/pdf/1702.00098)

