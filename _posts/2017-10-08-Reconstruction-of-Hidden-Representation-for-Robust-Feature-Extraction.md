---
layout: post
title: "Reconstruction of Hidden Representation for Robust Feature Extraction"
date: 2017-10-08 15:48:37
categories: arXiv_CV
tags: arXiv_CV Represenation_Learning
author: Zeng Yu, Tianrui Li, Ning Yu, Yi Pan, Hongmei Chen, Bing Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to develop a new and robust approach to feature representation. Motivated by the success of Auto-Encoders, we first theoretical summarize the general properties of all algorithms that are based on traditional Auto-Encoders: 1) The reconstruction error of the input or corrupted input can not be lower than a lower bound, which can be viewed as a guiding principle for reconstructing the input or corrupted input. 2) The reconstruction of a hidden representation achieving its ideal situation is the necessary condition for the reconstruction of the input to reach the ideal state. 3) Minimizing the Frobenius norm of the Jacobian matrix has a deficiency and may result in a much worse local optimum value. 4) Minimizing the reconstruction error of the hidden representation is more robust than minimizing the Frobenius norm of the Jacobian matrix. Based on the above analysis, we propose a new model termed Double Denoising Auto-Encoders (DDAEs), which uses corruption and reconstruction on both the input and the hidden representation. We demonstrate that the proposed model is highly flexible and extensible. We also show that for handling inessential features, our model is more robust than Denoising Auto-Encoders (DAEs). Comparative experiments illustrate that our model is significantly better for representation learning than the state-of-the-art models.

##### Abstract (translated by Google)
本文旨在开发一种新的强大的特征表示方法。在Auto-Encoder成功的推动下，我们首先对基于传统Auto-Encoder算法的所有算法的一般性质进行了理论总结：1）输入或损坏输入的重构误差不能低于下限，被视为重建输入或损坏输入的指导原则。 2）隐形表达的重构达到理想状态是重构输入达到理想状态的必要条件。 3）最小化雅可比矩阵的Frobenius范数有一个缺陷，并可能导致更糟糕的局部最优值。 4）最小化隐藏表示的重构误差比最小化雅可比矩阵的Frobenius范数更加鲁棒。基于上述分析，我们提出了一个新的模型称为双重去噪自动编码器（DDAEs），它使用输入和隐藏表示的腐败和重构。我们证明了所提出的模型是高度灵活和可扩展的。我们还表明，为了处理无关紧要的特性，我们的模型比去噪自动编码器（DAE）更强大。比较实验表明，我们的模型比最先进的模型在表示学习方面要好得多。

##### URL
[https://arxiv.org/abs/1710.02844](https://arxiv.org/abs/1710.02844)

##### PDF
[https://arxiv.org/pdf/1710.02844](https://arxiv.org/pdf/1710.02844)

