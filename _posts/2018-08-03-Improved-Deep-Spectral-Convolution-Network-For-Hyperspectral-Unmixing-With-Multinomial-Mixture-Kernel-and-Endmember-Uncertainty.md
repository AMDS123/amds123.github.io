---
layout: post
title: "Improved Deep Spectral Convolution Network For Hyperspectral Unmixing With Multinomial Mixture Kernel and Endmember Uncertainty"
date: 2018-08-03 07:40:25
categories: arXiv_CV
tags: arXiv_CV GAN
author: Savas Ozkan, Gozde Bozdagi Akar
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we propose a novel framework for hyperspectral unmixing by using a modular neural network structure while addressing the endmember uncertainty in our formulation. We present critical contributions throughout the manuscript: First, to improve the separability for hyperspectral data, we modify deep spectral convolution networks (DSCNs) that lead to more stable and accurate results. Second, we introduce a multinomial mixture kernel with a neural network (NN) which mimics the Gaussian Mixture Model (GMM) to estimate the abundances per-pixel by using the low-dimension representations obtained from the improved DSCN. Moreover, as formulated in the spectral variability assumption, a NN module is incorporated to capture the uncertainty term. Third, to optimize the coefficients of the multinomial model and the uncertainty term, Wasserstein GAN is exploited in particular since it has several theoretical benefits over the expectation maximization. Fourth, all neural network modules are formulated as an end-to-end hyperspectral unmixing pipeline that can be optimized with backpropagation by using a stochastic gradient-based solver. Experiments are performed on real and synthetic datasets. The results validate that the proposed method obtains state-of-the-art hyperspectral unmixing performance particularly on the real datasets compared to the baseline techniques.

##### Abstract (translated by Google)
在这项研究中，我们通过使用模块化神经网络结构提出了一个新的高光谱分离框架，同时解决了我们的配方中的端元不确定性。我们在整个手稿中提出了重要贡献：首先，为了改善高光谱数据的可分离性，我们修改了深度光谱卷积网络（DSCN），从而获得更稳定和准确的结果。其次，我们引入了具有神经网络（NN）的多项式混合核，其模拟高斯混合模型（GMM）以通过使用从改进的DSCN获得的低维表示来估计每像素的丰度。此外，如在频谱可变性假设中所述，并入NN模块以捕获不确定性项。第三，为了优化多项式模型和不确定项的系数，特别利用Wasserstein GAN，因为它具有超过期望最大化的若干理论益处。第四，所有神经网络模块都被公式化为端到端高光谱非混合流水线，可以通过使用基于随机梯度的求解器进行反向传播来优化。在真实和合成数据集上进行实验。结果证实，与基线技术相比，所提出的方法获得了最先进的高光谱非混合性能，特别是在真实数据集上。

##### URL
[http://arxiv.org/abs/1808.01104](http://arxiv.org/abs/1808.01104)

##### PDF
[http://arxiv.org/pdf/1808.01104](http://arxiv.org/pdf/1808.01104)

