---
layout: post
title: "Towards the Limit of Network Quantization"
date: 2017-11-13 19:44:32
categories: arXiv_CV
tags: arXiv_CV Optimization Quantitative Relation
author: Yoojin Choi, Mostafa El-Khamy, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Network quantization is one of network compression techniques to reduce the redundancy of deep neural networks. It reduces the number of distinct network parameter values by quantization in order to save the storage for them. In this paper, we design network quantization schemes that minimize the performance loss due to quantization given a compression ratio constraint. We analyze the quantitative relation of quantization errors to the neural network loss function and identify that the Hessian-weighted distortion measure is locally the right objective function for the optimization of network quantization. As a result, Hessian-weighted k-means clustering is proposed for clustering network parameters to quantize. When optimal variable-length binary codes, e.g., Huffman codes, are employed for further compression, we derive that the network quantization problem can be related to the entropy-constrained scalar quantization (ECSQ) problem in information theory and consequently propose two solutions of ECSQ for network quantization, i.e., uniform quantization and an iterative solution similar to Lloyd's algorithm. Finally, using the simple uniform quantization followed by Huffman coding, we show from our experiments that the compression ratios of 51.25, 22.17 and 40.65 are achievable for LeNet, 32-layer ResNet and AlexNet, respectively.

##### Abstract (translated by Google)
网络量化是减少深度神经网络冗余的网络压缩技术之一。它通过量化来减少不同网络参数值的数量，以便为它们节省存储空间。在本文中，我们设计网络量化方案，以最大限度地减少由于压缩比率限制量化的性能损失。分析了量化误差与神经网络损失函数的定量关系，确定了Hessian加权失真测度是网络量化优化的局部正确目标函数。因此，提出了用Hessian加权的k均值聚类来对网络参数进行聚类量化。当采用最优变长二进制编码（例如霍夫曼编码）进行进一步压缩时，我们推导出网络量化问题可能与信息论中的熵约束标量量化（ECSQ）问题有关，因此提出了ECSQ用于网络量化，即均匀量化和类似于劳埃德算法的迭代解。最后，使用简单的均匀量化和霍夫曼编码，从我们的实验中可以看出，LeNet，32层ResNet和AlexNet的压缩比分别为51.25,22.17和40.65。

##### URL
[https://arxiv.org/abs/1612.01543](https://arxiv.org/abs/1612.01543)

##### PDF
[https://arxiv.org/pdf/1612.01543](https://arxiv.org/pdf/1612.01543)

