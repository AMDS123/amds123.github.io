---
layout: post
title: "Globally Variance-Constrained Sparse Representation and Its Application in Image Set Coding"
date: 2018-05-03 03:23:28
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sparse Optimization Relation
author: Xiang Zhang, Jiarui Sun, Siwei Ma, Zhouchen Lin, Jian Zhang, Shiqi Wang, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse representation leads to an efficient way to approximately recover a signal by the linear composition of a few bases from a learnt dictionary, based on which various successful applications have been achieved. However, in the scenario of data compression, its efficiency and popularity are hindered. It is because of the fact that encoding sparsely distributed coefficients may consume more bits for representing the index of nonzero coefficients. Therefore, introducing an accurate rate-constraint in sparse coding and dictionary learning becomes meaningful, which has not been fully exploited in the context of sparse representation. According to the Shannon entropy inequality, the variance of a Gaussian distributed data bounds its entropy, indicating the actual bitrate can be well estimated by its variance. Hence, a Globally Variance-Constrained Sparse Representation (GVCSR) model is proposed in this work, where a variance-constrained rate term is introduced to the optimization process. Specifically, we employ the Alternating Direction Method of Multipliers (ADMM) to solve the non-convex optimization problem for sparse coding and dictionary learning, both of them have shown the state-of-the-art rate-distortion performance for image representation. Furthermore, we investigate the potential of applying the GVCSR algorithm in the practical image set compression, where the optimized dictionary is trained to efficiently represent the images captured in similar scenarios by implicitly utilizing inter-image correlations. Experimental results have demonstrated superior rate-distortion performance against the state-of-the-art methods.

##### Abstract (translated by Google)
稀疏表示导致通过来自学习字典的几个碱基的线性组合来近似地恢复信号的有效方式，基于其实现了各种成功的应用。但是，在数据压缩的情况下，其效率和普及受到阻碍。这是因为编码稀疏分布系数可能消耗更多比特来表示非零系数的索引。因此，在稀疏编码和字典学习中引入精确的速率约束变得有意义，这在稀疏表示的背景下还没有被充分利用。根据Shannon熵不等式，高斯分布数据的方差限制了其熵，表明实际比特率可以通过其方差很好地估计。因此，本文提出了一个全局方差约束稀疏表示（GVCSR）模型，其中方差约束率项引入优化过程。具体而言，我们采用交替方向乘法器（ADMM）来解决稀疏编码和字典学习的非凸优化问题，两者都显示了图像表示的最新速率失真性能。此外，我们研究了在实际图像集合压缩中应用GVCSR算法的可能性，其中优化的字典被训练为通过隐式地利用图像间相关性来有效地表示在相似场景下捕获的图像。实验结果表明，相对于最先进的方法，速率失真性能优越。

##### URL
[http://arxiv.org/abs/1608.04902](http://arxiv.org/abs/1608.04902)

##### PDF
[http://arxiv.org/pdf/1608.04902](http://arxiv.org/pdf/1608.04902)

