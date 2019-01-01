---
layout: post
title: "Monocular 3D Pose Recovery via Nonconvex Sparsity with Theoretical Analysis"
date: 2018-12-29 06:23:11
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Knowledge Optimization Inference
author: Jianqiao Wangni, Dahua Lin, Ji Liu, Kostas Daniilidis, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
For recovering 3D object poses from 2D images, a prevalent method is to pre-train an over-complete dictionary $\mathcal D=\{B_i\}_i^D$ of 3D basis poses. During testing, the detected 2D pose $Y$ is matched to dictionary by $Y \approx \sum_i M_i B_i$ where $\{M_i\}_i^D=\{c_i \Pi R_i\}$, by estimating the rotation $R_i$, projection $\Pi$ and sparse combination coefficients $c \in \mathbb R_{+}^D$. In this paper, we propose non-convex regularization $H(c)$ to learn coefficients $c$, including novel leaky capped $\ell_1$-norm regularization (LCNR), \begin{align*} H(c)=\alpha \sum_{i } \min(|c_i|,\tau)+ \beta \sum_{i } \max(| c_i|,\tau), \end{align*} where $0\leq \beta \leq \alpha$ and $0&lt;\tau$ is a certain threshold, so the invalid components smaller than $\tau$ are composed with larger regularization and other valid components with smaller regularization. We propose a multi-stage optimizer with convex relaxation and ADMM. We prove that the estimation error $\mathcal L(l)$ decays w.r.t. the stages $l$, \begin{align*} Pr\left(\mathcal L(l) &lt; \rho^{l-1} \mathcal L(0) + \delta \right) \geq 1- \epsilon, \end{align*} where $0&lt; \rho &lt;1, 0&lt;\delta, 0&lt;\epsilon \ll 1$. Experiments on large 3D human datasets like H36M are conducted to support our improvement upon previous approaches. To the best of our knowledge, this is the first theoretical analysis in this line of research, to understand how the recovery error is affected by fundamental factors, e.g. dictionary size, observation noises, optimization times. We characterize the trade-off between speed and accuracy towards real-time inference in applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11295](http://arxiv.org/abs/1812.11295)

##### PDF
[http://arxiv.org/pdf/1812.11295](http://arxiv.org/pdf/1812.11295)

