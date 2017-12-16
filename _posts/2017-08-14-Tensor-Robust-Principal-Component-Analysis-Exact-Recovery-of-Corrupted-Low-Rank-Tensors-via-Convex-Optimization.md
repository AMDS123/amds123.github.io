---
layout: post
title: "Tensor Robust Principal Component Analysis: Exact Recovery of Corrupted Low-Rank Tensors via Convex Optimization"
date: 2017-08-14 15:42:05
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Optimization
author: Canyi Lu, Jiashi Feng, Yudong Chen, Wei Liu, Zhouchen Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the Tensor Robust Principal Component (TRPCA) problem which extends the known Robust PCA \cite{RPCA} to the tensor case. Our model is based on a new tensor Singular Value Decomposition (t-SVD) \cite{kilmer2011factorization} and its induced tensor tubal rank and tensor nuclear norm. Consider that we have a 3-way tensor $\bm{\mathcal{X}}\in\mathbb{R}^{n_1\times n_2\times n_3}$ such that $\bm{\mathcal{X}}=\bm{\mathcal{L}}_0+\bm{\mathcal{S}}_0$, where $\bm{\mathcal{L}}_0$ has low tubal rank and $\bm{\mathcal{S}}_0$ is sparse. Is that possible to recover both components? In this work, we prove that under certain suitable assumptions, we can recover both the low-rank and the sparse components exactly by simply solving a convex program whose objective is a weighted combination of the tensor nuclear norm and the $\ell_1$-norm, i.e., \begin{align*} \min_{\bm{\mathcal{L}},\bm{\mathcal{E}}} \ \|{\bm{\mathcal{L}}}\|_*+\lambda\|{\bm{\mathcal{E}}}\|_1, \ \text{s.t.} \ \bm{\mathcal{X}}=\bm{\mathcal{L}}+\bm{\mathcal{E}}, \end{align*} where $\lambda= {1}/{\sqrt{\max(n_1,n_2)n_3}}$. Interestingly, TRPCA involves RPCA as a special case when $n_3=1$ and thus it is a simple and elegant tensor extension of RPCA. Also numerical experiments verify our theory and the application for the image denoising demonstrates the effectiveness of our method.

##### Abstract (translated by Google)
本文研究张量鲁棒主成分（TRPCA）问题，将已知的鲁棒PCA \ cite {RPCA}扩展到张量情况。我们的模型是基于一个新的张量奇异值分解（t-SVD）\引用{kilmer2011factorization}及其诱导张量输管和张量核范数。考虑在\ mathbb {R} ^ {n_1 \ times n_2 \ times n_3} $中有一个三元张量$ \ bm {\ mathcal {X}} \，这样$ \ bm {\ mathcal {X}} = \ bm {\ mathcal {L}} _ 0+ \ bm {\ mathcal {S}} _ 0 $，其中$ \ bm {\ mathcal {L}} _ 0 $具有低输卵管等级和$ \ bm {\ mathcal {S}} _0 $是稀疏的。是否有可能恢复这两个组件？在这项工作中，我们证明了在一定的适当的假设下，我们可以通过简单地求解一个凸规划来恢复低秩和稀疏分量，其目标是张量核范数和$ \ ell_1 $ -norm的加权组合，即\ begin {align *} \ min _ {\ bm {\ mathcal {L}}，\ bm {\ mathcal {E}}} \ \ | {\ bm {\ mathcal {L}}} + \ lambda \ | {\ bm {\ mathcal {E}}} \ | _1，\ \ text {st} \ \ bm {\ mathcal {X}} = \ bm {\ mathcal {L}} + \ bm { \ mathcal {E}}，\ end {align *}其中$ \ lambda = {1} / {\ sqrt {\ max（n_1，n_2）n_3}} $。有趣的是，当$ n_3 = 1 $时，TRPCA将RPCA作为一种特殊情况，因此它是RPCA简单而优雅的张量扩展。数值实验验证了我们的理论，图像去噪的应用证明了我们的方法的有效性。

##### URL
[https://arxiv.org/abs/1708.04181](https://arxiv.org/abs/1708.04181)

##### PDF
[https://arxiv.org/pdf/1708.04181](https://arxiv.org/pdf/1708.04181)

