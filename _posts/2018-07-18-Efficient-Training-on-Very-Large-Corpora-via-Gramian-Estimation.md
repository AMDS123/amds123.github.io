---
layout: post
title: "Efficient Training on Very Large Corpora via Gramian Estimation"
date: 2018-07-18 23:45:33
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Walid Krichene, Nicolas Mayoraz, Steffen Rendle, Li Zhang, Xinyang Yi, Lichan Hong, Ed Chi, John Anderson
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of learning similarity functions over very large corpora using neural network embedding models. These models are typically trained using SGD with sampling of random observed and unobserved pairs, with a number of samples that grows quadratically with the corpus size, making it expensive to scale to very large corpora. We propose new efficient methods to train these models without having to sample unobserved pairs. Inspired by matrix factorization, our approach relies on adding a global quadratic penalty to all pairs of examples and expressing this term as the matrix-inner-product of two generalized Gramians. We show that the gradient of this term can be efficiently computed by maintaining estimates of the Gramians, and develop variance reduction schemes to improve the quality of the estimates. We conduct large-scale experiments that show a significant improvement in training time and generalization quality compared to traditional sampling methods.

##### Abstract (translated by Google)
我们使用神经网络嵌入模型研究了在非常大的语料库中学习相似性函数的问题。这些模型通常使用SGD进行训练，对随机观察和未观察对进行采样，其中许多样本与语料库大小成二次方，这使得扩展到非常大的语料库的成本很高。我们提出了新的有效方法来训练这些模型，而无需对未观察到的对进行采样。受矩阵分解的启发，我们的方法依赖于对所有示例对添加全局二次惩罚，并将该术语表达为两个广义Gramians的矩阵内积。我们表明，通过维持Gramians的估计可以有效地计算该项的梯度，并开发方差减少方案以提高估计的质量。与传统的采样方法相比，我们进行了大规模的实验，显示培训时间和综合质量的显着改善。

##### URL
[https://arxiv.org/abs/1807.07187](https://arxiv.org/abs/1807.07187)

##### PDF
[https://arxiv.org/pdf/1807.07187](https://arxiv.org/pdf/1807.07187)

