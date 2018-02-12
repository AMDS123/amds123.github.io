---
layout: post
title: "Complex ISNMF: a Phase-Aware Model for Monaural Audio Source Separation"
date: 2018-02-09 07:38:05
categories: arXiv_SD
tags: arXiv_SD
author: Paul Magron, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a phase-aware probabilistic model for audio source separation. Classical source models in the short-term Fourier transform domain use circularly-symmetric Gaussian or Poisson random variables. This is equivalent to assuming that the phase of each source is uniformly distributed, which is not suitable for exploiting the underlying structure of the phase. Drawing on preliminary works, we introduce here a Bayesian anisotropic Gaussian source model in which the phase is no longer uniform. Such a model permits us to favor a phase value that originates from a signal model through a Markov chain prior structure. The variance of the latent variables are structured with nonnegative matrix factorization (NMF). The resulting model is called complex Itakura-Saito NMF (ISNMF) since it generalizes the ISNMF model to the case of non-isotropic variables. It combines the advantages of ISNMF, which uses a distortion measure adapted to audio and yields a set of estimates which preserve the overall energy of the mixture, and of complex NMF, which enables one to account for some phase constraints. We derive a generalized expectation-maximization algorithm to estimate the model parameters. Experiments conducted on a musical source separation task in a semi-informed setting show that the proposed approach outperforms state-of-the-art phase-aware separation techniques.

##### Abstract (translated by Google)
本文介绍了一个音频源分离的相位感知概率模型。短期傅立叶变换域中的经典源模型使用循环对称的高斯或泊松随机变量。这相当于假设每个源的相位是均匀分布的，这不适用于利用相位的基础结构。在前期工作的基础上，我们在这里介绍一个贝叶斯各向异性高斯源模型，其中相位不再一致。这样的模型允许我们倾向于通过马尔可夫链结构的信号模型产生相位值。潜变量的方差由非负矩阵分解（NMF）构成。由于它将ISNMF模型推广到非各向同性变量的情况，因此得到的模型被称为复杂的Itakura-Saito NMF（ISNMF）。它结合了ISNMF的优势，ISNMF使用适合音频的失真度量，并产生一组保​​留混合物总体能量的估计值，以及复杂的NMF值，从而可以解释一些相位约束。我们导出了一个广义的期望最大化算法来估计模型参数。在半知情设置下对音源分离任务进行的实验表明，所提出的方法优于最先进的相识别分离技术。

##### URL
[http://arxiv.org/abs/1802.03156](http://arxiv.org/abs/1802.03156)

##### PDF
[http://arxiv.org/pdf/1802.03156](http://arxiv.org/pdf/1802.03156)

