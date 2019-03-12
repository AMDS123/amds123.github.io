---
layout: post
title: "SSN: Learning Sparse Switchable Normalization via SparsestMax"
date: 2019-03-09 12:48:52
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Deep_Learning
author: Wenqi Shao, Tianjian Meng, Jingyu Li, Ruimao Zhang, Yudian Li, Xiaogang Wang, Ping Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Normalization methods improve both optimization and generalization of ConvNets. To further boost performance, the recently-proposed switchable normalization (SN) provides a new perspective for deep learning: it learns to select different normalizers for different convolution layers of a ConvNet. However, SN uses softmax function to learn importance ratios to combine normalizers, leading to redundant computations compared to a single normalizer. This work addresses this issue by presenting Sparse Switchable Normalization (SSN) where the importance ratios are constrained to be sparse. Unlike $\ell_1$ and $\ell_0$ constraints that impose difficulties in optimization, we turn this constrained optimization problem into feed-forward computation by proposing SparsestMax, which is a sparse version of softmax. SSN has several appealing properties. (1) It inherits all benefits from SN such as applicability in various tasks and robustness to a wide range of batch sizes. (2) It is guaranteed to select only one normalizer for each normalization layer, avoiding redundant computations. (3) SSN can be transferred to various tasks in an end-to-end manner. Extensive experiments show that SSN outperforms its counterparts on various challenging benchmarks such as ImageNet, Cityscapes, ADE20K, and Kinetics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03793](https://arxiv.org/abs/1903.03793)

##### PDF
[https://arxiv.org/pdf/1903.03793](https://arxiv.org/pdf/1903.03793)

