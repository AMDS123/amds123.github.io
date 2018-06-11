---
layout: post
title: "Training Faster by Separating Modes of Variation in Batch-normalized Models"
date: 2018-06-07 20:41:09
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Image_Classification Classification
author: Mahdi M. Kalayeh, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Batch Normalization (BN) is essential to effectively train state-of-the-art deep Convolutional Neural Networks (CNN). It normalizes inputs to the layers during training using the statistics of each mini-batch. In this work, we study BN from the viewpoint of Fisher kernels. We show that assuming samples within a mini-batch are from the same probability density function, then BN is identical to the Fisher vector of a Gaussian distribution. That means BN can be explained in terms of kernels that naturally emerge from the probability density function of the underlying data distribution. However, given the rectifying non-linearities employed in CNN architectures, distribution of inputs to the layers show heavy tail and asymmetric characteristics. Therefore, we propose approximating underlying data distribution not with one, but a mixture of Gaussian densities. Deriving Fisher vector for a Gaussian Mixture Model (GMM), reveals that BN can be improved by independently normalizing with respect to the statistics of disentangled sub-populations. We refer to our proposed soft piecewise version of BN as Mixture Normalization (MN). Through extensive set of experiments on CIFAR-10 and CIFAR-100, we show that MN not only effectively accelerates training image classification and Generative Adversarial networks, but also reaches higher quality models.

##### Abstract (translated by Google)
批量标准化（BN）对于有效培训最先进的深度卷积神经网络（CNN）至关重要。它使用每个小批量的统计数据对训练过程中各层的输入进行归一化。在这项工作中，我们从Fisher核心的角度研究BN。我们证明，假设小批量样本来自同一个概率密度函数，那么BN与高斯分布的Fisher向量相同。这意味着BN可以根据基本数据分布的概率密度函数自然产生的内核来解释。然而，考虑到CNN架构中采用的整流非线性，输入层的分布显示出重尾和非对称特性。因此，我们建议不要用一个来近似数据分布，而要用高斯密度混合。导出用于高斯混合模型（GMM）的Fisher矢量，揭示了BN可以通过独立地归一化关于解开的子群的统计来改进。我们将我们提出的BN软分段版本称为混合标准化（MN）。通过对CIFAR-10和CIFAR-100的大量实验，我们发现MN不仅能有效加速训练图像分类和生成敌对网络，而且还能达到更高质量的模型。

##### URL
[http://arxiv.org/abs/1806.02892](http://arxiv.org/abs/1806.02892)

##### PDF
[http://arxiv.org/pdf/1806.02892](http://arxiv.org/pdf/1806.02892)

