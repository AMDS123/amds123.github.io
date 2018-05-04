---
layout: post
title: "A Missing Information Loss function for implicit feedback datasets"
date: 2018-04-30 22:38:05
categories: arXiv_AI
tags: arXiv_AI Recommendation
author: Juan Arévalo, Juan Ramón Duque, Marco Creatura
mathjax: true
---

* content
{:toc}

##### Abstract
Latent factor models with implicit feedback typically treat unobserved user-item interactions (i.e. missing information) as negative feedback. This is frequently done either through negative sampling (point-wise loss) or with a ranking loss function (pair- or list-wise estimation). Since a zero preference recommendation is a valid solution for most common objective functions, regarding unknown values as actual zeros results in users having a zero preference recommendation for most of the available items. In this paper we propose a novel objective function, the Missing Information Loss (MIL) function, that explicitly forbids treating unobserved user-item interactions as positive or negative feedback. We apply this loss to a user--based Denoising Autoencoder and compare it with other known objective functions such as cross-entropy (both point-- and pair--wise) or the recently proposed multinomial log-likelihood. The MIL function achieves best results in ranking-aware metrics when applied to the Movielens-20M and Netflix datasets, slightly above those obtained with cross-entropy in point-wise estimation. Furthermore, such a competitive performance is obtained while recommending popular items less frequently, a valuable feature for Recommender Systems with a large catalogue of products.

##### Abstract (translated by Google)
具有隐式反馈的潜在因子模型通常将未观测到的用户项目交互（即缺失信息）视为负面反馈。这通常是通过负面抽样（逐点损失）或排名损失函数（对或列表估计）来完成的。由于零偏好建议是大多数常见目标函数的有效解决方案，因此对于未知值而言，实际为零会导致用户对大多数可用项目有零偏好建议。在本文中，我们提出了一种新颖的目标函数，缺失信息丢失（MIL）函数，明确禁止将未观察到的用户项目交互作为正面或负面反馈。我们将这种损失应用于基于用户的去噪自动编码器，并将其与其他已知的目标函数（如交叉熵（包括点和成对）或最近提出的多项式对数似然比较）进行比较。当应用于Movielens-20M和Netflix数据集时，MIL函数在排名感知度量方面取得了最佳结果，略高于用交叉熵进行的逐点估计。此外，这样的竞争性表现在获得较少推荐流行项目的同时获得，这对于具有大型产品目录的推荐系统是一个有价值的特征。

##### URL
[https://arxiv.org/abs/1805.00121](https://arxiv.org/abs/1805.00121)

##### PDF
[https://arxiv.org/pdf/1805.00121](https://arxiv.org/pdf/1805.00121)

