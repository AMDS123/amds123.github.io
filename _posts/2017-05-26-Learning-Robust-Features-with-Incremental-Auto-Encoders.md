---
layout: post
title: "Learning Robust Features with Incremental Auto-Encoders"
date: 2017-05-26 08:30:41
categories: arXiv_CV
tags: arXiv_CV Attention Optimization Classification
author: Yanan Li, Donghui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically learning features, especially robust features, has attracted much attention in the machine learning community. In this paper, we propose a new method to learn non-linear robust features by taking advantage of the data manifold structure. We first follow the commonly used trick of the trade, that is learning robust features with artificially corrupted data, which are training samples with manually injected noise. Following the idea of the auto-encoder, we first assume features should contain much information to well reconstruct the input from its corrupted copies. However, merely reconstructing clean input from its noisy copies could make data manifold in the feature space noisy. To address this problem, we propose a new method, called Incremental Auto-Encoders, to iteratively denoise the extracted features. We assume the noisy manifold structure is caused by a diffusion process. Consequently, we reverse this specific diffusion process to further contract this noisy manifold, which results in an incremental optimization of model parameters . Furthermore, we show these learned non-linear features can be stacked into a hierarchy of features. Experimental results on real-world datasets demonstrate the proposed method can achieve better classification performances.

##### Abstract (translated by Google)
自动学习功能，特别是强大的功能，在机器学习界引起了很大的关注。在本文中，我们提出了一种利用数据流形结构学习非线性鲁棒特征的新方法。我们首先遵循交易的常用技巧，即学习人为破坏数据的鲁棒性特征，这些数据是手动注入噪声的训练样本。遵循自动编码器的思想，我们首先假设特征应该包含许多信息来很好地重构来自其损坏副本的输入。然而，仅仅从其噪声副本中重构干净的输入可能使特征空间中的数据流形噪声较大。为了解决这个问题，我们提出了一种新的方法，称为增量自动编码器，迭代去噪提取的功能。我们假设噪声流形结构是由扩散过程引起的。因此，我们逆向这个特定的扩散过程来进一步收缩这个噪声流形，这导致了模型参数的增量优化。此外，我们展示了这些学习到的非线性特征可以堆叠成一个层次的特征。对实际数据集的实验结果表明，该方法可以取得较好的分类性能。

##### URL
[https://arxiv.org/abs/1705.09476](https://arxiv.org/abs/1705.09476)

##### PDF
[https://arxiv.org/pdf/1705.09476](https://arxiv.org/pdf/1705.09476)

