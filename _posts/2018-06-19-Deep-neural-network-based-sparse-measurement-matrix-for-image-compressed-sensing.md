---
layout: post
title: "Deep neural network based sparse measurement matrix for image compressed sensing"
date: 2018-06-19 02:53:12
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Wenxue Cui, Feng Jiang, Xinwei Gao, Wen Tao, Debin Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian random matrix (GRM) has been widely used to generate linear measurements in compressed sensing (CS) of natural images. However, there actually exist two disadvantages with GRM in practice. One is that GRM has large memory requirement and high computational complexity, which restrict the applications of CS. Another is that the CS measurements randomly obtained by GRM cannot provide sufficient reconstruction performances. In this paper, a Deep neural network based Sparse Measurement Matrix (DSMM) is learned by the proposed convolutional network to reduce the sampling computational complexity and improve the CS reconstruction performance. Two sub networks are included in the proposed network, which are the sampling sub-network and the reconstruction sub-network. In the sampling sub-network, the sparsity and the normalization are both considered by the limitation of the storage and the computational complexity. In order to improve the CS reconstruction performance, a reconstruction sub-network are introduced to help enhance the sampling sub-network. So by the offline iterative training of the proposed end-to-end network, the DSMM is generated for accurate measurement and excellent reconstruction. Experimental results demonstrate that the proposed DSMM outperforms GRM greatly on representative CS reconstruction methods

##### Abstract (translated by Google)
高斯随机矩阵（GRM）已被广泛用于在自然图像的压缩感测（CS）中生成线性测量。然而，实际上GRM实际上存在两个缺点。一是GRM具有较大的内存需求和较高的计算复杂度，限制了CS的应用。另一个是由GRM随机获得的CS测量不能提供足够的重建性能。本文提出了一种基于深度神经网络的稀疏测量矩阵（DSMM），以减少采样计算复杂度，提高CS重构性能。提出的网络中包含两个子网络，即采样子网络和重建子网络。在采样子网中，稀疏性和归一化都是由存储的限制和计算复杂度来考虑的。为了提高CS重建性能，引入了重建子网络来帮助提升采样子网络。因此，通过对所提议的端到端网络进行离线迭代训练，可生成DSMM以进行精确测量和出色的重建。实验结果表明，所提出的DSMM在代表性CS重建方法上优于GRM

##### URL
[http://arxiv.org/abs/1806.07026](http://arxiv.org/abs/1806.07026)

##### PDF
[http://arxiv.org/pdf/1806.07026](http://arxiv.org/pdf/1806.07026)

