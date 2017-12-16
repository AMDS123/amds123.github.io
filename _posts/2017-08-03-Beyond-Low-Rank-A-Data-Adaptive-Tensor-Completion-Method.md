---
layout: post
title: "Beyond Low Rank: A Data-Adaptive Tensor Completion Method"
date: 2017-08-03 05:51:27
categories: arXiv_CV
tags: arXiv_CV Inference
author: Lei Zhang, Wei Wei, Qinfeng Shi, Chunhua Shen, Anton van den Hengel, Yanning Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Low rank tensor representation underpins much of recent progress in tensor completion. In real applications, however, this approach is confronted with two challenging problems, namely (1) tensor rank determination; (2) handling real tensor data which only approximately fulfils the low-rank requirement. To address these two issues, we develop a data-adaptive tensor completion model which explicitly represents both the low-rank and non-low-rank structures in a latent tensor. Representing the non-low-rank structure separately from the low-rank one allows priors which capture the important distinctions between the two, thus enabling more accurate modelling, and ultimately, completion. Through defining a new tensor rank, we develop a sparsity induced prior for the low-rank structure, with which the tensor rank can be automatically determined. The prior for the non-low-rank structure is established based on a mixture of Gaussians which is shown to be flexible enough, and powerful enough, to inform the completion process for a variety of real tensor data. With these two priors, we develop a Bayesian minimum mean squared error estimate (MMSE) framework for inference which provides the posterior mean of missing entries as well as their uncertainty. Compared with the state-of-the-art methods in various applications, the proposed model produces more accurate completion results.

##### Abstract (translated by Google)
低阶张量表示是张量完成最近进展的基础。然而，在实际应用中，这种方法面临两个具有挑战性的问题，即（1）张量等级确定; （2）处理实际的张量数据只能满足低秩需求。为了解决这两个问题，我们开发了一个数据自适应张量完成模型，明确表示潜在张量中的低秩和非低秩结构。将非低级别结构与低级别结构分开表示，可以使得前者能够捕捉两者之间的重要区别，从而实现更精确的建模，最终完成。通过定义一个新的张量秩，我们在低秩结构之前产生一个先验稀疏度，张量秩可以自动确定。非低秩结构的先验建立在高斯混合的基础上，被证明具有足够的灵活性和足够的强度，以通知完成过程的各种实际张量数据。有了这两个先验，我们开发了贝叶斯最小均方误差估计（MMSE）推理框架，它提供了缺失条目的后验均值以及它们的不确定性。与各种应用中的最新方法相比，所提出的模型产生更准确的完成结果。

##### URL
[https://arxiv.org/abs/1708.01008](https://arxiv.org/abs/1708.01008)

##### PDF
[https://arxiv.org/pdf/1708.01008](https://arxiv.org/pdf/1708.01008)

