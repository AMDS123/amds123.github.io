---
layout: post
title: "Tensor Robust Principal Component Analysis: Exact Recovery of Corrupted Low-Rank Tensors via Convex Optimization"
date: 2017-12-09 01:55:55
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Optimization
author: Canyi Lu, Jiashi Feng, Yudong Chen, Wei Liu, Zhouchen Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the Tensor Robust Principal Component (TRPCA) problem which extends the known Robust PCA (Cand${\`e}$s et al. 2011) to the tensor case. Our model is based on a new tensor Singular Value Decomposition (t-SVD) (Kilmer and Martin 2011) and its induced tensor tubal rank and tensor nuclear norm. Consider that we have a 3-way tensor ${\mathcal{X}}\in\mathbb{R}^{n_1\times n_2\times n_3}$ such that ${\mathcal{X}}={\mathcal{L}}_0+{\mathcal{E}}_0$, where ${\mathcal{L}}_0$ has low tubal rank and ${\mathcal{E}}_0$ is sparse. Is that possible to recover both components? In this work, we prove that under certain suitable assumptions, we can recover both the low-rank and the sparse components exactly by simply solving a convex program whose objective is a weighted combination of the tensor nuclear norm and the $\ell_1$-norm, i.e.,\min_{{\mathcal{L}},\ {\mathcal{E}}} \ \|{{\mathcal{L}}}\|_*+\lambda\|{{\mathcal{E}}}\|_1, \ \text{s.t.} \ {\mathcal{X}}={\mathcal{L}}+{\mathcal{E}}, where $\lambda= {1}/{\sqrt{\max(n_1,n_2)n_3}}$. Interestingly, TRPCA involves RPCA as a special case when $n_3=1$ and thus it is a simple and elegant tensor extension of RPCA. Also numerical experiments verify our theory and the application for the image denoising demonstrates the effectiveness of our method.

##### Abstract (translated by Google)
本文研究张量鲁棒主成分（TRPCA）问题，将已知的Robust PCA（Cand $ {e} $ s et al。2011）扩展到张量情形。我们的模型基于新的张量奇异值分解（t-SVD）（Kilmer和Martin，2011）及其诱导张量输管和张量核范数。考虑在\ mathbb {R} ^ {n_1 \ times n_2 \ times n_3} $中有一个三元张量$ {\ mathcal {X}} \，这样$ {\ mathcal {X}} = {\ mathcal {其中$ {\ mathcal {L}} _ 0 $具有较低的输卵管排列，$ {\ mathcal {E}} _ 0 $是稀疏的。是否有可能恢复这两个组件？在这项工作中，我们证明了在一定的适当的假设下，我们可以通过简单地求解一个凸规划来恢复低秩和稀疏分量，其目标是张量核范数和$ \ ell_1 $ -norm的加权组合，即\ min_ {\ mathcal {L}}，\ {\ mathcal {E}}} \ \ {{\ mathcal {L}}} \ | _ * + \ lambda \ | {{\ mathcal {E $ \ lambda = {1} / {\ sqrt {}}} \ {\ mathcal {L}} {{\ mathcal { {\ MAX（N_1，N_2）N_3}} $。有趣的是，当$ n_3 = 1 $时，TRPCA将RPCA作为一种特殊情况，因此它是RPCA简单而优雅的张量扩展。数值实验验证了我们的理论，图像去噪的应用证明了我们的方法的有效性。

##### URL
[http://arxiv.org/abs/1708.04181](http://arxiv.org/abs/1708.04181)

##### PDF
[http://arxiv.org/pdf/1708.04181](http://arxiv.org/pdf/1708.04181)

