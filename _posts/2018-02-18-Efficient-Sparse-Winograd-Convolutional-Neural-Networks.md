---
layout: post
title: "Efficient Sparse-Winograd Convolutional Neural Networks"
date: 2018-02-18 12:29:05
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Xingyu Liu, Jeff Pool, Song Han, William J. Dally
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) are computationally intensive, which limits their application on mobile devices. Their energy is dominated by the number of multiplies needed to perform the convolutions. Winograd's minimal filtering algorithm (Lavin, 2015) and network pruning (Han et al., 2015) can reduce the operation count, but these two methods cannot be directly combined $-$ applying the Winograd transform fills in the sparsity in both the weights and the activations. We propose two modifications to Winograd-based CNNs to enable these methods to exploit sparsity. First, we move the ReLU operation into the Winograd domain to increase the sparsity of the transformed activations. Second, we prune the weights in the Winograd domain to exploit static weight sparsity. For models on CIFAR-10, CIFAR-100 and ImageNet datasets, our method reduces the number of multiplications by $10.4\times$, $6.8\times$ and $10.8\times$ respectively with loss of accuracy less than $0.1\%$, outperforming previous baselines by $2.0\times$-$3.0\times$. We also show that moving ReLU to the Winograd domain allows more aggressive pruning.

##### Abstract (translated by Google)
卷积神经网络（CNN）计算量很大，这限制了它们在移动设备上的应用。它们的能量主要取决于执行卷积所需的乘法次数。 Winograd的最小滤波算法（Lavin，2015）和网络修剪（Han等，2015）可以减少运算次数，但是这两种方法不能直接结合使用，因为Winograd变换填补了权重的稀疏性，激活。我们建议对基于Winograd的CNN进行两项修改，以使这些方法能够利用稀疏性。首先，我们将ReLU操作移入Winograd域以增加已转换激活的稀疏性。其次，我们修剪Winograd域中的权重以利用静态权重稀疏性。对于CIFAR-10，CIFAR-100和ImageNet数据集上的模型，我们的方法分别将乘法次数减少$ 10.4 \ times $，$ 6.8 \ times $和$ 10.8 \ times $，精度损失小于$ 0.1 \％$，优于以前的基线减$ 2.0 \ times $  -  $ 3.0 \ times $。我们还表明，将ReLU移动到Winograd域允许更积极的修剪。

##### URL
[http://arxiv.org/abs/1802.06367](http://arxiv.org/abs/1802.06367)

##### PDF
[http://arxiv.org/pdf/1802.06367](http://arxiv.org/pdf/1802.06367)

