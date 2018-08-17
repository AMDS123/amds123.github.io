---
layout: post
title: "A Missing Information Loss function for implicit feedback datasets"
date: 2018-08-16 08:16:50
categories: arXiv_AI
tags: arXiv_AI Recommendation
author: Juan Ar&#xe9;valo, Juan Ram&#xf3;n Duque, Marco Creatura
mathjax: true
---

* content
{:toc}

##### Abstract
Latent factor models for Recommender Systems with implicit feedback typically treat unobserved user-item interactions (i.e. missing information) as negative feedback. This is frequently done either through negative sampling (point--wise loss) or with a ranking loss function (pair-- or list--wise estimation). Since a zero preference recommendation is a valid solution for most common objective functions, regarding unknown values as actual zeros results in users having a zero preference recommendation for most of the available items. In this paper we propose a novel objective function, the \emph{Missing Information Loss} (MIL), that explicitly forbids treating unobserved user-item interactions as positive or negative feedback. We apply this loss to both traditional Matrix Factorization and user--based Denoising Autoencoder, and compare it with other established objective functions such as cross-entropy (both point- and pair-wise) or the recently proposed multinomial log-likelihood. MIL achieves competitive performance in ranking-aware metrics when applied to three datasets. Furthermore, we show that such a relevance in the recommendation is obtained while displaying popular items less frequently (up to a $20 \%$ decrease with respect to the best competing method). This debiasing from the recommendation of popular items favours the appearance of infrequent items (up to a $50 \%$ increase of long-tail recommendations), a valuable feature for Recommender Systems with a large catalogue of products.

##### Abstract (translated by Google)
具有隐式反馈的推荐系统的潜在因子模型通常将未观察到的用户 - 项目交互（即，缺失信息）视为负反馈。这通常通过负抽样（逐点丢失）或排名损失函数（对 - 或列表 - 明智估计）来完成。由于零偏好推荐是对于大多数常见目标函数的有效解决方案，因此将未知值作为实际零导致用户对大多数可用项具有零偏好推荐。在本文中，我们提出了一种新的目标函数，即\ emph {Missing Information Loss}（MIL），明确禁止将未观察到的用户 - 项目交互视为正面或负面反馈。我们将此损失应用于传统的矩阵分解和基于用户的去噪自动编码器，并将其与其他已建立的目标函数（如交叉熵（点对和成对）或最近提出的多项对数似然）进行比较。当应用于三个数据集时，MIL在排名感知指标中实现了竞争性能。此外，我们表明在推荐热门项目的同时获得推荐中的这种相关性（相对于最佳竞争方法，最多降低20美元\％$）。这种对流行物品推荐的贬值有利于出现不常见的物品（长尾推荐高达50美元/％），这对于具有大量产品目录的推荐系统而言非常有用。

##### URL
[http://arxiv.org/abs/1805.00121](http://arxiv.org/abs/1805.00121)

##### PDF
[http://arxiv.org/pdf/1805.00121](http://arxiv.org/pdf/1805.00121)

