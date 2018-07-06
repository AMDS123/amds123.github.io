---
layout: post
title: "Understanding kernel size in blind deconvolution"
date: 2018-07-05 13:29:32
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Quantitative
author: Li Si-Yao, Dongwei Ren, Qian Yin, Ping Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Most blind deconvolution methods usually pre-define a large kernel size to guarantee the support domain. Blur kernel estimation error is likely to be introduced, and is proportional to kernel size. In this paper, we experimentally and theoretically show the reason of noises introduction in oversized kernel by demonstrating that sizeable kernels lead to lower optimization cost. To eliminate this adverse effect, we propose a low rank-based regularization on blur kernel by analyzing the structural information in degraded kernels. Compared with the sparsity prior, e.g., $\ell_\alpha$-norm, our regularization term can effectively suppress random noises in oversized kernels. On benchmark test dataset, the proposed method is compared with several state-of-the-art methods, and can achieve better quantitative score. Especially, the improvement margin is much more significant for oversized blur kernels. We also validate the proposed method on real-world blurry images.

##### Abstract (translated by Google)
大多数盲解卷积方法通常预先定义大的内核大小以保证支持域。可能会引入模糊内核估计错误，并且与内核大小成比例。在本文中，我们通过证明大尺寸内核导致较低的优化成本，在实验和理论上显示了超大内核中噪声引入的原因。为了消除这种不利影响，我们通过分析退化内核中的结构信息，提出了一种基于低秩的模糊核正则化。与稀疏先验（例如$ \ ell_ \ alpha $ -norm）相比，我们的正则化项可以有效地抑制超大核中的随机噪声。在基准测试数据集上，将所提出的方法与几种最先进的方法进行比较，并可以获得更好的定量分数。特别是，对于超大模糊内核，改进余量更为显着。我们还验证了在真实世界模糊图像上提出的方法。

##### URL
[http://arxiv.org/abs/1706.01797](http://arxiv.org/abs/1706.01797)

##### PDF
[http://arxiv.org/pdf/1706.01797](http://arxiv.org/pdf/1706.01797)

