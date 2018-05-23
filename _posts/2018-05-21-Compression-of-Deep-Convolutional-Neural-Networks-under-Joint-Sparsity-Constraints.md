---
layout: post
title: "Compression of Deep Convolutional Neural Networks under Joint Sparsity Constraints"
date: 2018-05-21 22:00:21
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Optimization
author: Yoojin Choi, Mostafa El-Khamy, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the optimization of deep convolutional neural networks (CNNs) such that they provide good performance while having reduced complexity if deployed on either conventional systems utilizing spatial-domain convolution or lower complexity systems designed for Winograd convolution. Furthermore, we explore the universal quantization and compression of these networks. In particular, the proposed framework produces one compressed model whose convolutional filters are sparse not only in the spatial domain but also in the Winograd domain. Hence, one compressed model can be deployed universally on any platform, without need for re-training on the deployed platform, and the sparsity of its convolutional filters can be exploited for further complexity reduction in either domain. To get a better compression ratio, the sparse model is compressed in the spatial domain which has a less number of parameters. From our experiments, we obtain $24.2\times$, $47.7\times$ and $35.4\times$ compressed models for ResNet-18, AlexNet and CT-SRCNN, while their computational complexity is also reduced by $4.5\times$, $5.1\times$ and $23.5\times$, respectively.

##### Abstract (translated by Google)
我们考虑深层卷积神经网络（CNN）的优化，使得它们在使用空间域卷积的常规系统或为Winograd卷积设计的较低复杂度系统上部署时提供了良好的性能，同时降低了复杂度。此外，我们探索这些网络的通用量化和压缩。具体而言，所提出的框架产生一个压缩模型，其卷积滤波器不仅在空间域中而且在Winograd域中都是稀疏的。因此，一个压缩模型可以在任何平台上普遍部署，而无需在部署的平台上重新训练，并且其卷积滤波器的稀疏性可用于进一步降低任何域中的复杂度。为了获得更好的压缩比，稀疏模型在具有较少参数的空间域中被压缩。从我们的实验中，我们获得ResNet-18，AlexNet和CT-SRCNN的$ 24.2 \ times $，$ 47.7 \ times $和$ 35.4 \ times $压缩模型，而它们的计算复杂度也减少了$ 4.5 \ times $，$ 5.1 \ times $和$ 23.5 \ times $，分别。

##### URL
[https://arxiv.org/abs/1805.08303](https://arxiv.org/abs/1805.08303)

##### PDF
[https://arxiv.org/pdf/1805.08303](https://arxiv.org/pdf/1805.08303)

