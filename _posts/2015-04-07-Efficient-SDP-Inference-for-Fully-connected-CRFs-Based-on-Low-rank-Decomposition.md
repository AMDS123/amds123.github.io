---
layout: post
title: "Efficient SDP Inference for Fully-connected CRFs Based on Low-rank Decomposition"
date: 2015-04-07 06:43:50
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Inference Relation
author: Peng Wang, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional Random Fields (CRF) have been widely used in a variety of computer vision tasks. Conventional CRFs typically define edges on neighboring image pixels, resulting in a sparse graph such that efficient inference can be performed. However, these CRFs fail to model long-range contextual relationships. Fully-connected CRFs have thus been proposed. While there are efficient approximate inference methods for such CRFs, usually they are sensitive to initialization and make strong assumptions. In this work, we develop an efficient, yet general algorithm for inference on fully-connected CRFs. The algorithm is based on a scalable SDP algorithm and the low- rank approximation of the similarity/kernel matrix. The core of the proposed algorithm is a tailored quasi-Newton method that takes advantage of the low-rank matrix approximation when solving the specialized SDP dual problem. Experiments demonstrate that our method can be applied on fully-connected CRFs that cannot be solved previously, such as pixel-level image co-segmentation.

##### Abstract (translated by Google)
条件随机场（CRF）已被广泛用于各种计算机视觉任务。常规CRF通常定义相邻图像像素上的边缘，导致稀疏图形，使得可以执行有效的推理。但是，这些CRF不能模拟远距离情景关系。因此提出了完全连接的CRF。虽然对于这样的CRF存在有效的近似推断方法，但是它们通常对初始化敏感并且做出强烈的假设。在这项工作中，我们开发了一个有效的，但通用的算法推断完全连接CRFs。该算法基于可扩展的SDP算法和相似度/核矩阵的低秩近似。该算法的核心是一种量身定制的拟牛顿法，在解决专门的SDP对偶问题时利用低秩矩阵逼近。实验证明，我们的方法可以应用于以前无法解决的全连接CRF，如像素级图像协同分割。

##### URL
[https://arxiv.org/abs/1504.01492](https://arxiv.org/abs/1504.01492)

##### PDF
[https://arxiv.org/pdf/1504.01492](https://arxiv.org/pdf/1504.01492)

