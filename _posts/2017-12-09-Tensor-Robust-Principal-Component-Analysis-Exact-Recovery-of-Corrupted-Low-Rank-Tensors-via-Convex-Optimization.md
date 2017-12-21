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
This paper studies the Tensor Robust Principal Component (TRPCA) problem which extends the known Robust PCA (Cand${\`e}$s et al. 2011) to the tensor case. Our model is based on a new tensor Singular Value Decomposition (t-SVD) (Kilmer and Martin 2011) and its induced tensor tubal rank and tensor nuclear norm. Consider that we have a 3-way tensor ${\mathcal{X}}\in\mathbb{R}^{n_1\times n_2\times n_3}$ such that ${\mathcal{X}}={\mathcal{L}}_0+{\mathcal{E}}_0$, where ${\mathcal{L}}_0$ has low tubal rank and ${\mathcal{E}}_0$ is sparse. Is that possible to recover both components? In this work, we prove that under certain suitable assumptions, we can recover both the low-rank and the sparse components exactly by simply solving a convex program whose objective is a weighted combination of the tensor nuclear norm and the $\ell_1$-norm, i.e.,\min_{{\mathcal{L}},\ {\mathcal{E}}} \ \|{{\mathcal{L}}}\|_*+\lambda\|{{\mathcal{E}}}\|_1, \ \text{s.t.} \ {\mathcal{X}}={\mathcal{L}}+{\mathcal{E}}, where $\lambda= {1}/{\sqrt{\max(n_1,n_2)n_3}}$. Interestingly, TRPCA involves RPCA as a special case when $n_3=1$ and thus it is a simple and elegant tensor extension of RPCA. Also numerical experiments verify our theory and the application for the image denoising demonstrates the effectiveness of our method.

##### URL
[http://arxiv.org/abs/1708.04181](http://arxiv.org/abs/1708.04181)

##### PDF
[http://arxiv.org/pdf/1708.04181](http://arxiv.org/pdf/1708.04181)

