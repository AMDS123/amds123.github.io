---
layout: post
title: "Fiber Orientation Estimation Guided by a Deep Network"
date: 2017-05-19 06:37:34
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Chuyang Ye, Jerry L. Prince
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion magnetic resonance imaging (dMRI) is currently the only tool for noninvasively imaging the brain's white matter tracts. The fiber orientation (FO) is a key feature computed from dMRI for fiber tract reconstruction. Because the number of FOs in a voxel is usually small, dictionary-based sparse reconstruction has been used to estimate FOs with a relatively small number of diffusion gradients. However, accurate FO estimation in regions with complex FO configurations in the presence of noise can still be challenging. In this work we explore the use of a deep network for FO estimation in a dictionary-based framework and propose an algorithm named Fiber Orientation Reconstruction guided by a Deep Network (FORDN). FORDN consists of two steps. First, we use a smaller dictionary encoding coarse basis FOs to represent the diffusion signals. To estimate the mixture fractions of the dictionary atoms (and thus coarse FOs), a deep network is designed specifically for solving the sparse reconstruction problem. Here, the smaller dictionary is used to reduce the computational cost of training. Second, the coarse FOs inform the final FO estimation, where a larger dictionary encoding dense basis FOs is used and a weighted l1-norm regularized least squares problem is solved to encourage FOs that are consistent with the network output. FORDN was evaluated and compared with state-of-the-art algorithms that estimate FOs using sparse reconstruction on simulated and real dMRI data, and the results demonstrate the benefit of using a deep network for FO estimation.

##### Abstract (translated by Google)
扩散磁共振成像（dMRI）是目前唯一的无创成像大脑白质束的工具。纤维取向（FO）是dMRI计算纤维束重建的关键特征。由于体素中FO的数量通常很少，因此使用基于字典的稀疏重构来估计具有相对较小扩散梯度的FO。然而，在存在噪声的情况下，在具有复杂FO配置的区域中的准确的FO估计仍然是具有挑战性的。在这项工作中，我们探索了在基于字典的框架中使用深度网络进行FO估计，并提出了一种由深度网络（FORDN）引导的名为“Fiber Orientation Reconstruction”的算法。 FORDN包含两个步骤。首先，我们使用一个较小的字典编码粗基FO来表示扩散信号。为了估计字典原子的混合分数（从而粗略的FO），专门设计了深度网络来解决稀疏重建问题。在这里，使用较小的字典来减少训练的计算成本。其次，粗糙的FO通知最终的FO估计，其中使用编码密集基FO的较大字典，并且解决加权的l1范数正则化最小二乘问题以鼓励与网络输出一致的FO。对FORDN进行了评估，并与使用对模拟和真实dMRI数据进行稀疏重构来估计FO的最新算法进行了比较，结果证明了使用深度网络进行FO估计的好处。

##### URL
[https://arxiv.org/abs/1705.06870](https://arxiv.org/abs/1705.06870)

##### PDF
[https://arxiv.org/pdf/1705.06870](https://arxiv.org/pdf/1705.06870)

