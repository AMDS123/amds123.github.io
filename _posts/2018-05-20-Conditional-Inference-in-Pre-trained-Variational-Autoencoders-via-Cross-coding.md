---
layout: post
title: "Conditional Inference in Pre-trained Variational Autoencoders via Cross-coding"
date: 2018-05-20 16:13:09
categories: arXiv_CV
tags: arXiv_CV Inference Quantitative
author: Ga Wu, Justin Domke, Scott Sanner
mathjax: true
---

* content
{:toc}

##### Abstract
Variational Autoencoders (VAEs) are a popular generative model, but one in which conditional inference can be challenging. If the decomposition into query and evidence variables is fixed, conditional VAEs provide an attractive solution. To support arbitrary queries, one is generally reduced to Markov Chain Monte Carlo sampling methods that can suffer from long mixing times. In this paper, we propose an idea we term cross-coding to approximate the distribution over the latent variables after conditioning on an evidence assignment to some subset of the variables. This allows generating query samples without retraining the full VAE. We experimentally evaluate three variations of cross-coding showing that (i) two can be quickly trained for different decompositions of evidence and query and (ii) they quantitatively and qualitatively outperform Hamiltonian Monte Carlo.

##### Abstract (translated by Google)
变分自动编码器（VAEs）是一种流行的生成模型，但条件推理可能具有挑战性。如果对查询和证据变量的分解是固定的，则条件VAE提供了一个有吸引力的解决方案。为了支持任意查询，通常将其简化为马尔可夫链蒙特卡罗采样方法，该方法可能会遇到混合时间过长的问题。在本文中，我们提出了一个想法，我们称交叉编码来在对变量的某个子集进行证据分配后进行调节，以近似潜在变量的分布。这样可以生成查询样本，而无需重新培训完整的VAE。我们通过实验评估交叉编码的三种变化，表明（i）两种可以快速训练用于证据和查询的不同分解，（ii）它们在数量上和质量上胜过哈密顿蒙特卡罗。

##### URL
[https://arxiv.org/abs/1805.07785](https://arxiv.org/abs/1805.07785)

##### PDF
[https://arxiv.org/pdf/1805.07785](https://arxiv.org/pdf/1805.07785)

