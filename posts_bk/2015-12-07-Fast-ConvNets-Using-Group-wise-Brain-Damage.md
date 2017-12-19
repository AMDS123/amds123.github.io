---
layout: post
title: "Fast ConvNets Using Group-wise Brain Damage"
date: 2015-12-07 18:11:36
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Vadim Lebedev, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We revisit the idea of brain damage, i.e. the pruning of the coefficients of a neural network, and suggest how brain damage can be modified and used to speedup convolutional layers. The approach uses the fact that many efficient implementations reduce generalized convolutions to matrix multiplications. The suggested brain damage process prunes the convolutional kernel tensor in a group-wise fashion by adding group-sparsity regularization to the standard training process. After such group-wise pruning, convolutions can be reduced to multiplications of thinned dense matrices, which leads to speedup. In the comparison on AlexNet, the method achieves very competitive performance.

##### Abstract (translated by Google)
我们重新审视脑损伤的概念，即修剪神经网络的系数，并提出如何修改脑损伤并用于加速卷积层。该方法使用了许多有效的实现将广义卷积减少到矩阵乘法的事实。建议的脑损伤过程通过在标准训练过程中增加群稀疏正则化来以分组方式修剪卷积核张量。经过这样的分组修剪之后，卷积可以减少到稀疏密集矩阵的乘法，导致加速。在AlexNet上的比较中，该方法实现了非常有竞争力的性能。

##### URL
[https://arxiv.org/abs/1506.02515](https://arxiv.org/abs/1506.02515)

##### PDF
[https://arxiv.org/pdf/1506.02515](https://arxiv.org/pdf/1506.02515)

