---
layout: post
title: "Spectrally Grouped Total Variation Reconstruction for Scatter Imaging Using ADMM"
date: 2016-01-29 17:27:37
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Ikenna Odinaka, Yan Kaganovsky, Joel A. Greenberg, Mehadi Hassan, David G. Politte, Joseph A. O'Sullivan, Lawrence Carin, David J. Brady
mathjax: true
---

* content
{:toc}

##### Abstract
We consider X-ray coherent scatter imaging, where the goal is to reconstruct momentum transfer profiles (spectral distributions) at each spatial location from multiplexed measurements of scatter. Each material is characterized by a unique momentum transfer profile (MTP) which can be used to discriminate between different materials. We propose an iterative image reconstruction algorithm based on a Poisson noise model that can account for photon-limited measurements as well as various second order statistics of the data. To improve image quality, previous approaches use edge-preserving regularizers to promote piecewise constancy of the image in the spatial domain while treating each spectral bin separately. Instead, we propose spectrally grouped regularization that promotes piecewise constant images along the spatial directions but also ensures that the MTPs of neighboring spatial bins are similar, if they contain the same material. We demonstrate that this group regularization results in improvement of both spectral and spatial image quality. We pursue an optimization transfer approach where convex decompositions are used to lift the problem such that all hyper-voxels can be updated in parallel and in closed-form. The group penalty introduces a challenge since it is not directly amendable to these decompositions. We use the alternating directions method of multipliers (ADMM) to replace the original problem with an equivalent sequence of sub-problems that are amendable to convex decompositions, leading to a highly parallel algorithm. We demonstrate the performance on real data.

##### Abstract (translated by Google)
我们考虑X射线相干散射成像，其目标是从多重散射测量结果重建每个空间位置处的动量转移轮廓（光谱分布）。每种材料的特点是独特的动量转移轮廓（MTP），可以用来区分不同的材料。我们提出了一种基于Poisson噪声模型的迭代图像重建算法，该模型可以解释光子受限测量以及数据的各种二阶统计量。为了提高图像质量，先前的方法使用边缘保持正则化（regularizer）来在空间域中促进图像的分段恒定性，同时分别处理每个谱单元。相反，我们提出光谱分组正则化，它沿着空间方向促进分段恒定的图像，但是如果它们包含相同的材料，也确保相邻空间分箱的MTP是相似的。我们证明，这个组正则化导致光谱和空间图像质量的改善。我们追求一种优化转移方法，其中使用凸分解来解除问题，使得所有超体元可以以并行和闭合形式更新。团体惩罚带来了挑战，因为它不能直接修正这些分解。我们使用乘法器的交替方向方法（ADMM）来替换原来的问题，用等效的子问题序列来修正凸分解，从而得到高度并行的算法。我们演示真实数据的性能。

##### URL
[https://arxiv.org/abs/1601.08201](https://arxiv.org/abs/1601.08201)

##### PDF
[https://arxiv.org/pdf/1601.08201](https://arxiv.org/pdf/1601.08201)

