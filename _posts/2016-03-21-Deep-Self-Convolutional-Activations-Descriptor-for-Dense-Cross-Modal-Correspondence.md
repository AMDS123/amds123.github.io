---
layout: post
title: "Deep Self-Convolutional Activations Descriptor for Dense Cross-Modal Correspondence"
date: 2016-03-21 05:30:48
categories: arXiv_CV
tags: arXiv_CV CNN
author: Seungryong Kim, Dongbo Min, Stephen Lin, Kwanghoon Sohn
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel descriptor, called deep self-convolutional activations (DeSCA), designed for establishing dense correspondences between images taken under different imaging modalities, such as different spectral ranges or lighting conditions. Motivated by descriptors based on local self-similarity (LSS), we formulate a novel descriptor by leveraging LSS in a deep architecture, leading to better discriminative power and greater robustness to non-rigid image deformations than state-of-the-art cross-modality descriptors. The DeSCA first computes self-convolutions over a local support window for randomly sampled patches, and then builds self-convolution activations by performing an average pooling through a hierarchical formulation within a deep convolutional architecture. Finally, the feature responses on the self-convolution activations are encoded through a spatial pyramid pooling in a circular configuration. In contrast to existing convolutional neural networks (CNNs) based descriptors, the DeSCA is training-free (i.e., randomly sampled patches are utilized as the convolution kernels), is robust to cross-modal imaging, and can be densely computed in an efficient manner that significantly reduces computational redundancy. The state-of-the-art performance of DeSCA on challenging cases of cross-modal image pairs is demonstrated through extensive experiments.

##### Abstract (translated by Google)
我们提出了一个新的描述符，称为深自我卷积激活（DeSCA），旨在建立在不同的成像模式，如不同的光谱范围或光照条件下拍摄的图像之间的密集对应。基于局部自相似性（LSS）的描述符的驱动，我们制定了一个新的描述符通过利用LSS在深层次的体系结构，导致更好的判别力和更强大的非刚性图像变形比国家的最先进的交叉，形式描述符。 DeSCA首先在局部支持窗口上计算随机采样补丁的自卷积，然后通过在深度卷积体系结构内通过分层公式进行平均池化来建立自卷积激活。最后，对自卷积激活的特征响应通过以圆形配置的空间金字塔池进行编码。与现有的基于卷积神经网络（CNN）的描述符相比，DeSCA是无需训练的（即随机采样的贴片被用作卷积核），对于交叉模态成像是鲁棒的，并且可以以有效的方式密集计算这大大减少了计算冗余。通过广泛的实验证明了DeSCA在跨模态图像对的具有挑战性的情况下的最新性能。

##### URL
[https://arxiv.org/abs/1603.06327](https://arxiv.org/abs/1603.06327)

##### PDF
[https://arxiv.org/pdf/1603.06327](https://arxiv.org/pdf/1603.06327)

