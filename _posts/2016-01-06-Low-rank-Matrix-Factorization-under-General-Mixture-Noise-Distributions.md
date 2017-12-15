---
layout: post
title: "Low-rank Matrix Factorization under General Mixture Noise Distributions"
date: 2016-01-06 02:52:30
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Xiangyong Cao, Qian Zhao, Deyu Meng, Yang Chen, Zongben Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Many computer vision problems can be posed as learning a low-dimensional subspace from high dimensional data. The low rank matrix factorization (LRMF) represents a commonly utilized subspace learning strategy. Most of the current LRMF techniques are constructed on the optimization problems using L1-norm and L2-norm losses, which mainly deal with Laplacian and Gaussian noises, respectively. To make LRMF capable of adapting more complex noise, this paper proposes a new LRMF model by assuming noise as Mixture of Exponential Power (MoEP) distributions and proposes a penalized MoEP (PMoEP) model by combining the penalized likelihood method with MoEP distributions. Such setting facilitates the learned LRMF model capable of automatically fitting the real noise through MoEP distributions. Each component in this mixture is adapted from a series of preliminary super- or sub-Gaussian candidates. Moreover, by facilitating the local continuity of noise components, we embed Markov random field into the PMoEP model and further propose the advanced PMoEP-MRF model. An Expectation Maximization (EM) algorithm and a variational EM (VEM) algorithm are also designed to infer the parameters involved in the proposed PMoEP and the PMoEP-MRF model, respectively. The superseniority of our methods is demonstrated by extensive experiments on synthetic data, face modeling, hyperspectral image restoration and background subtraction.

##### Abstract (translated by Google)
许多计算机视觉问题可以被认为是从高维数据中学习低维子空间。低秩矩阵分解（LRMF）表示通常使用的子空间学习策略。目前大多数LRMF技术都是基于L1范数和L2范数损失的优化问题构建的，主要处理Laplacian和Gaussian噪声。为了使LRMF能够适应更复杂的噪声，本文将噪声假设为指数幂分布（MoEP）分布，提出了一种新的LRMF模型，并将惩罚似然方法与MoEP分布相结合，提出了一种惩罚MoEP（PMoEP）模型。这样的设置有助于学习的LRMF模型能够通过MoEP分布自动拟合真实噪声。这个混合物中的每个成分都是从一系列初步的超高斯或亚高斯候选者中进行调整的。此外，通过促进噪声分量的局部连续性，将马尔可夫随机场嵌入到PMoEP模型中，并进一步提出了先进的PMoEP-MRF模型。还设计了期望最大化（EM）算法和变分EM（VEM）算法，以分别推断所提出的PMoEP和PMoEP-MRF模型中涉及的参数。通过对合成数据，人脸建模，高光谱图像恢复和背景扣除的广泛实验，证明了我们方法的超高性能。

##### URL
[https://arxiv.org/abs/1601.01060](https://arxiv.org/abs/1601.01060)

##### PDF
[https://arxiv.org/pdf/1601.01060](https://arxiv.org/pdf/1601.01060)

