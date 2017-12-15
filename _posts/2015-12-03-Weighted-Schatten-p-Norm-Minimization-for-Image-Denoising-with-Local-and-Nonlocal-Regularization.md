---
layout: post
title: "Weighted Schatten $p$-Norm Minimization for Image Denoising with Local and Nonlocal Regularization"
date: 2015-12-03 09:37:42
categories: arXiv_CV
tags: arXiv_CV Regularization Quantitative
author: Yuan Xie
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a patch-wise low-rank based image denoising method with constrained variational model involving local and nonlocal regularization. On one hand, recent patch-wise methods can be represented as a low-rank matrix approximation problem whose convex relaxation usually depends on nuclear norm minimization (NNM). Here, we extend the NNM to the nonconvex schatten p-norm minimization with additional weights assigned to different singular values, which is referred to as the Weighted Schatten p-Norm Minimization (WSNM). An efficient algorithm is also proposed to solve the WSNM problem. The proposed WSNM not only gives better approximation to the original low-rank assumption, but also considers physical meanings of different data components. On the other hand, due to the naive aggregation schema which integrates all the denoised patches into a whole image, current patch-wise denoising methods always produce various degree of artifacts in denoised results. Therefore, to further reduce artifacts, a data-driven regularizer called Steering Total Variation (STV) combined with nonlocal TV is derived for a variational model, which imposes local and nonlocal consistency constraints on the patch-wise denoised image. A highly simple but efficient algorithm is proposed to solve this variational model with convergence guarantee. Both WSNM and local \& nonlocal consistent regularization are integrated into an iterative restoration framework to produce final results. Extensive experimental testing shows, both qualitatively and quantitatively, that the proposed method can effectively remove noise, as well as reduce artifacts compared with state-of-the-art methods.

##### Abstract (translated by Google)
本文提出了一种基于斑块方式的基于局部和非局部正则化的约束变分模型的图像去噪方法。一方面，最近的贴片方法可以表示为低阶矩阵逼近问题，其凸凸松弛通常取决于核范数最小化（NNM）。在这里，我们将NNM扩展到非凸线性p范数最小化，并将附加权重分配给不同的奇异值，称为加权Schatten p模范最小化（WSNM）。还提出了一种高效的算法来解决WSNM问题。所提出的WSNM不仅较好地逼近了原始的低秩假设，而且考虑了不同数据分量的物理意义。另一方面，由于将所有去噪后的斑块整合成整幅图像的朴素的聚合方案，目前的斑点去噪方法总是在去噪后的结果中产生各种程度的伪影。因此，为了进一步减少伪像，为了变分模型导出了称为Steering Total Variation（STV）与非本地TV的数据驱动正规化器，其针对面片去噪图像施加局部和非局部一致性约束。提出了一种高度简单而有效的算法来求解具有收敛性的变分模型。 WSNM和本地非本地一致正则化都被整合到迭代恢复框架中以产生最终结果。广泛的实验测试表明，在定性和定量两方面，提出的方法可以有效地消除噪音，以及减少文物与最先进的方法相比。

##### URL
[https://arxiv.org/abs/1501.01372](https://arxiv.org/abs/1501.01372)

##### PDF
[https://arxiv.org/e-print/1501.01372](https://arxiv.org/e-print/1501.01372)

