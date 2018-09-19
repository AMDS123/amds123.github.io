---
layout: post
title: "Compressed Sensing Parallel MRI with Adaptive Shrinkage TV Regularization"
date: 2018-09-18 12:23:55
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Raji Susan Mathew, Joseph Suresh Paul
mathjax: true
---

* content
{:toc}

##### Abstract
Compressed sensing (CS) methods in magnetic resonance imaging (MRI) offer rapid acquisition and improved image quality but require iterative reconstruction schemes with regularization to enforce sparsity. Regardless of the difficulty in obtaining a fast numerical solution, the total variation (TV) regularization is a preferred choice due to its edge-preserving and structure recovery capabilities. While many approaches have been proposed to overcome the non-differentiability of the TV cost term, an iterative shrinkage based formulation allows recovering an image through recursive application of linear filtering and soft thresholding. However, providing an optimal setting for the regularization parameter is critical due to its direct impact on the rate of convergence as well as steady state error. In this paper, a regularizer adaptively varying in the derivative space is proposed, that follows the generalized discrepancy principle (GDP). The implementation proceeds by adaptively reducing the discrepancy level expressed as the absolute difference between TV norms of the consistency error and the sparse approximation error. A criterion based on the absolute difference between TV norms of consistency and sparse approximation errors is used to update the threshold. Application of the adaptive shrinkage TV regularizer to CS recovery of parallel MRI (pMRI) and temporal gradient adaptation in dynamic MRI are shown to result in improved image quality with accelerated convergence. In addition, the adaptive TV-based iterative shrinkage (ATVIS) provides a significant speed advantage over the fast iterative shrinkage-thresholding algorithm (FISTA).

##### Abstract (translated by Google)
磁共振成像（MRI）中的压缩感知（CS）方法提供快速采集和改善的图像质量，但需要具有正则化的迭代重建方案以实施稀疏性。无论获得快速数值解决方案的难度如何，由于其边缘保留和结构恢复能力，总变差（TV）正则化是优选的选择。虽然已经提出了许多方法来克服TV成本项的不可微分性，但是基于迭代收缩的公式允许通过线性滤波和软阈值的递归应用来恢复图像。然而，为正则化参数提供最佳设置是至关重要的，因为它直接影响收敛速度以及稳态误差。在本文中，提出了一种在导数空间中自适应变化的正则化器，它遵循广义差异原理（GDP）。通过自适应地减小差异等级来实现该实现，该差异等级表示为一致性误差的TV规范与稀疏近似误差之间的绝对差。基于电视规范的一致性和稀疏近似误差之间的绝对差异的标准用于更新阈值。自适应收缩电视正则化器在并行MRI（pMRI）的CS恢复和动态MRI中的时间梯度自适应中的应用被示出导致具有加速收敛的改善的图像质量。此外，基于自适应电视的迭代收缩（ATVIS）与快速迭代收缩 - 阈值算法（FISTA）相比具有显着的速度优势。

##### URL
[https://arxiv.org/abs/1809.06665](https://arxiv.org/abs/1809.06665)

##### PDF
[https://arxiv.org/pdf/1809.06665](https://arxiv.org/pdf/1809.06665)

