---
layout: post
title: "Multilinear Map Layer: Prediction Regularization by Structural Constraint"
date: 2015-07-30 09:34:30
categories: arXiv_CV
tags: arXiv_CV Regularization Prediction
author: Shuchang Zhou, Yuxin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose and study a technique to impose structural constraints on the output of a neural network, which can reduce amount of computation and number of parameters besides improving prediction accuracy when the output is known to approximately conform to the low-rankness prior. The technique proceeds by replacing the output layer of neural network with the so-called MLM layers, which forces the output to be the result of some Multilinear Map, like a hybrid-Kronecker-dot product or Kronecker Tensor Product. In particular, given an "autoencoder" model trained on SVHN dataset, we can construct a new model with MLM layer achieving 62\% reduction in total number of parameters and reduction of $\ell_2$ reconstruction error from 0.088 to 0.004. Further experiments on other autoencoder model variants trained on SVHN datasets also demonstrate the efficacy of MLM layers.

##### Abstract (translated by Google)
在本文中，我们提出并研究了一种对神经网络的输出施加结构约束的技术，除了在输出已知大致符合低秩先验之前提高预测准确度之外，还可以减少计算量和参数数量。该技术通过用所谓的MLM层代替神经网络的输出层来进行，这迫使输出是多线性映射的结果，如混合克罗内克点积或克罗内克张量积。特别是，在SVHN数据集上训练的“自编码器”模型中，我们可以构建一个新的MLM层模型，实现参数总数减少62％，并将$ \ ell_2 $重构误差从0.088减少到0.004。在SVHN数据集上训练的其他自编码器模型变体上的进一步实验也证明了MLM层的功效。

##### URL
[https://arxiv.org/abs/1507.08429](https://arxiv.org/abs/1507.08429)

##### PDF
[https://arxiv.org/pdf/1507.08429](https://arxiv.org/pdf/1507.08429)

