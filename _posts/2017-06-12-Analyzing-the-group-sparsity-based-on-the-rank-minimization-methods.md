---
layout: post
title: "Analyzing the group sparsity based on the rank minimization methods"
date: 2017-06-12 12:18:36
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Zhiyuan Zha, Xin Liu, Xiaohua Huang, Henglin Shi, Yingyue Xu, Qiong Wang, Lan Tang, Xinggan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse coding has achieved a great success in various image processing studies. However, there is not any benchmark to measure the sparsity of image patch/group because sparse discriminant conditions cannot keep unchanged. This paper analyzes the sparsity of group based on the strategy of the rank minimization. Firstly, an adaptive dictionary for each group is designed. Then, we prove that group-based sparse coding is equivalent to the rank minimization problem, and thus the sparse coefficient of each group is measured by estimating the singular values of each group. Based on that measurement, the weighted Schatten $p$-norm minimization (WSNM) has been found to be the closest solution to the real singular values of each group. Thus, WSNM can be equivalently transformed into a non-convex $\ell_p$-norm minimization problem in group-based sparse coding. To make the proposed scheme tractable and robust, the alternating direction method of multipliers (ADMM) is used to solve the $\ell_p$-norm minimization problem. Experimental results on two applications: image inpainting and image compressive sensing (CS) recovery have shown that the proposed scheme outperforms many state-of-the-art methods.

##### Abstract (translated by Google)
稀疏编码在各种图像处理研究中取得了巨大的成功。然而，由于稀疏判别条件不能保持不变，因此没有任何基准来衡量图像块/组的稀疏性。本文基于排名最小化策略分析了群体的稀疏性。首先，为每个组设计一个自适应字典。然后，证明了基于群组的稀疏编码等价于秩最小化问题，从而通过估计每个群的奇异值来度量每个群的稀疏系数。基于这种测量，已经发现加权的Schatten $ p $ -norm最小化（WSNM）是每个组的真实奇异值的最接近的解决方案。因此，在基于组的稀疏编码中，WSNM可以等价地变换成非凸的$ \ ell_p $ -norm最小化问题。为了使所提出的方案易于处理和鲁棒，使用乘法器的交替方向方法（ADMM）来解决$ \ ell_p $ -norm最小化问题。图像修复和图像压缩感知（CS）恢复的两个应用的实验结果表明，所提出的方案胜过许多最先进的方法。

##### URL
[https://arxiv.org/abs/1611.08983](https://arxiv.org/abs/1611.08983)

##### PDF
[https://arxiv.org/pdf/1611.08983](https://arxiv.org/pdf/1611.08983)

