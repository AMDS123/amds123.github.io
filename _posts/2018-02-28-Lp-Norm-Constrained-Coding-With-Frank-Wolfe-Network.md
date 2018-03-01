---
layout: post
title: "$L_p$-Norm Constrained Coding With Frank-Wolfe Network"
date: 2018-02-28 03:49:08
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse CNN Image_Classification Classification Gradient_Descent
author: Ke Sun, Zhangyang Wang, Dong Liu, Runsheng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of $L_p$-norm constrained coding, i.e. converting signal into code that lies inside the $L_p$-ball and most faithfully reconstructs the signal. While previous works known as sparse coding have addressed the cases of $\ell_0$ "norm" and $L_1$-norm, more general cases with other $p$ values, especially with unknown $p$, remain a difficulty. We propose the Frank-Wolfe Network (F-W Net), whose architecture is inspired by unrolling and truncating the Frank-Wolfe algorithm for solving an $L_p$-norm constrained problem. We show that the Frank-Wolfe solver for the $L_p$-norm constraint leads to a novel closed-form nonlinear unit, which is parameterized by $p$ and termed $pool_p$. The $pool_p$ unit links the conventional pooling, activation, and normalization operations, making F-W Net distinct from existing deep models either heuristically designed or converted from projection gradient descent or proximal algorithms. We further show that the hyper-parameter $p$ can be made learnable instead of pre-chosen in F-W Net, which gracefully solves the $L_p$-norm constrained coding problem with unknown $p$. A convolutional extension of F-W Net is then presented. We evaluate the performance of F-W Net on an extensive range of simulations to show the strong learning capability of F-W Net. We then adopt F-W Net or Convolutional F-W Net on a series of real-data tasks that are all formulated as $L_p$-norm constrained coding, including image classification, image denoising, and super-resolution, where F-W Net all demonstrates impressive effectiveness, flexibility, and robustness. In particular, F-W Net achieves significantly better performance than the state-of-the-art convolutional networks on image denoising, leading to more than 2 dB gain on the BSD-68 dataset.

##### Abstract (translated by Google)
我们研究$ L_p $ -norm约束编码的问题，即将信号转换为位于$ L_p $ -ball内的代码，并最忠实地重构信号。尽管以前的作品被称为稀疏编码，它们解决了$ \ ell_0 $“norm”和$ L_1 $ -norm的情况，但更常见的情况是使用其他$ p $值，尤其是未知的$ p $，仍然是一个难题。我们提出Frank-Wolfe网络（F-W网络），其架构受到展开和截断Frank-Wolfe算法以解决$ L_p $ -norm约束问题的启发。我们证明$ L_p $ -norm约束条件下的Frank-Wolfe求解器导致了一种新颖的封闭形式的非线性单元，它被$ p $参数化并被称为$ pool_p $。 $ pool_p $单元链接传统的池化，激活和规范化操作，使得F-W Net不同于现有的深度模型，不论是启发式设计还是从投影梯度下降法或近端算法转换而来。我们进一步表明，超参数$ p $可以被学习而不是在F-W Net中预先选择，它优雅地解决了未知$ p $的$ L_p $ -norm约束编码问题。然后呈现F-W网络的卷积延伸。我们在广泛的模拟范围内评估F-W Net的性能，以显示F-W Net强大的学习能力。然后，我们采用FW Net或Convolutional FW Net来处理一系列实际数据任务，这些任务都被制定为$ L_p $ -norm约束编码，包括图像分类，图像去噪和超分辨率，其中FW Net都表现出令人印象深刻的效果，灵活性和坚固性。尤其是，F-W Net在图像去噪方面的性能远远优于最先进的卷积网络，从而使BSD-68数据集的增益超过2 dB。

##### URL
[http://arxiv.org/abs/1802.10252](http://arxiv.org/abs/1802.10252)

##### PDF
[http://arxiv.org/pdf/1802.10252](http://arxiv.org/pdf/1802.10252)

