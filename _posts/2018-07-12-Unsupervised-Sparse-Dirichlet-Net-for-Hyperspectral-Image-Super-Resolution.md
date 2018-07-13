---
layout: post
title: "Unsupervised Sparse Dirichlet-Net for Hyperspectral Image Super-Resolution"
date: 2018-07-12 07:55:42
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse Deep_Learning
author: Ying Qu, Hairong Qi, Chiman Kwan
mathjax: true
---

* content
{:toc}

##### Abstract
In many computer vision applications, obtaining images of high resolution in both the spatial and spectral domains are equally important. However, due to hardware limitations, one can only expect to acquire images of high resolution in either the spatial or spectral domains. This paper focuses on hyperspectral image super-resolution (HSI-SR), where a hyperspectral image (HSI) with low spatial resolution (LR) but high spectral resolution is fused with a multispectral image (MSI) with high spatial resolution (HR) but low spectral resolution to obtain HR HSI. Existing deep learning-based solutions are all supervised that would need a large training set and the availability of HR HSI, which is unrealistic. Here, we make the first attempt to solving the HSI-SR problem using an unsupervised encoder-decoder architecture that carries the following uniquenesses. First, it is composed of two encoder-decoder networks, coupled through a shared decoder, in order to preserve the rich spectral information from the HSI network. Second, the network encourages the representations from both modalities to follow a sparse Dirichlet distribution which naturally incorporates the two physical constraints of HSI and MSI. Third, the angular difference between representations are minimized in order to reduce the spectral distortion. We refer to the proposed architecture as unsupervised Sparse Dirichlet-Net, or uSDN. Extensive experimental results demonstrate the superior performance of uSDN as compared to the state-of-the-art.

##### Abstract (translated by Google)
在许多计算机视觉应用中，在空间和光谱域中获得高分辨率的图像同样重要。然而，由于硬件限制，人们只能期望在空间或光谱域中获取高分辨率的图像。本文重点研究高光谱图像超分辨率（HSI-SR），其中具有低空间分辨率（LR）但高光谱分辨率的高光谱图像（HSI）与具有高空间分辨率（HR）的多光谱图像（MSI）融合但是低光谱分辨率以获得HR HSI。现有的基于深度学习的解决方案都受到监督，需要大量的培训和HR HSI的可用性，这是不现实的。在这里，我们首次尝试使用具有以下唯一性的无监督编码器 - 解码器架构来解决HSI-SR问题。首先，它由两个编码器 - 解码器网络组成，通过共享解码器耦合，以便保留来自HSI网络的丰富频谱信息。其次，网络鼓励两种方式的表示遵循稀疏的Dirichlet分布，其自然地结合了HSI和MSI的两个物理约束。第三，表示之间的角度差异被最小化以便减少光谱失真。我们将所提出的架构称为无监督稀疏Dirichlet-Net或uSDN。广泛的实验结果表明，与现有技术相比，uSDN具有优越的性能。

##### URL
[http://arxiv.org/abs/1804.05042](http://arxiv.org/abs/1804.05042)

##### PDF
[http://arxiv.org/pdf/1804.05042](http://arxiv.org/pdf/1804.05042)

