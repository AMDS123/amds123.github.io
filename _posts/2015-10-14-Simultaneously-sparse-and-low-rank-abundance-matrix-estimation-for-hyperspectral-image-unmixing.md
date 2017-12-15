---
layout: post
title: "Simultaneously sparse and low-rank abundance matrix estimation for hyperspectral image unmixing"
date: 2015-10-14 16:53:41
categories: arXiv_CV
tags: arXiv_CV Sparse Relation
author: Paris Giampouras, Konstantinos Themelis, Athanasios Rontogiannis, Konstantinos Koutroumbas
mathjax: true
---

* content
{:toc}

##### Abstract
In a plethora of applications dealing with inverse problems, e.g. in image processing, social networks, compressive sensing, biological data processing etc., the signal of interest is known to be structured in several ways at the same time. This premise has recently guided the research to the innovative and meaningful idea of imposing multiple constraints on the parameters involved in the problem under study. For instance, when dealing with problems whose parameters form sparse and low-rank matrices, the adoption of suitably combined constraints imposing sparsity and low-rankness, is expected to yield substantially enhanced estimation results. In this paper, we address the spectral unmixing problem in hyperspectral images. Specifically, two novel unmixing algorithms are introduced, in an attempt to exploit both spatial correlation and sparse representation of pixels lying in homogeneous regions of hyperspectral images. To this end, a novel convex mixed penalty term is first defined consisting of the sum of the weighted $\ell_1$ and the weighted nuclear norm of the abundance matrix corresponding to a small area of the image determined by a sliding square window. This penalty term is then used to regularize a conventional quadratic cost function and impose simultaneously sparsity and row-rankness on the abundance matrix. The resulting regularized cost function is minimized by a) an incremental proximal sparse and low-rank unmixing algorithm and b) an algorithm based on the alternating minimization method of multipliers (ADMM). The effectiveness of the proposed algorithms is illustrated in experiments conducted both on simulated and real data.

##### Abstract (translated by Google)
在处理反向问题的大量应用中，例如在图像处理，社交网络，压缩感知，生物数据处理等方面，已知感兴趣的信号以多种方式同时被构建。最近，这个前提指导了研究对于研究中涉及的参数施加多重约束的创新和有意义的想法。例如，当处理参数形成稀疏矩阵和低秩矩阵的问题时，采用适当的组合约束来施加稀疏性和低秩度，预期会产生显着增强的估计结果。在本文中，我们解决高光谱图像中的光谱解混问题。具体来说，引入了两种新的混合算法，试图利用位于高光谱图像的均匀区域中的像素的空间相关和稀疏表示。为此，首先定义一个新的凸混合惩罚项，其中加权$ \ ell_1 $和丰度矩阵的加权核范数的总和相当于一个滑动的方形窗口确定的图像的一个小区域。这个惩罚项然后被用来规范一个传统的二次代价函数，同时在丰度矩阵上加上稀疏性和行级。得到的正则化成本函数通过a）增量近邻稀疏和低秩解混算法和b）基于乘法器交替最小化方法（ADMM）的算法来最小化。所提出的算法的有效性在对模拟数据和真实数据进行的实验中说明。

##### URL
[https://arxiv.org/abs/1504.01515](https://arxiv.org/abs/1504.01515)

##### PDF
[https://arxiv.org/pdf/1504.01515](https://arxiv.org/pdf/1504.01515)

