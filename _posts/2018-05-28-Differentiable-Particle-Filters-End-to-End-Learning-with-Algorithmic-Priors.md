---
layout: post
title: "Differentiable Particle Filters: End-to-End Learning with Algorithmic Priors"
date: 2018-05-28 18:30:56
categories: arXiv_AI
tags: arXiv_AI Prediction Memory_Networks
author: Rico Jonschkowski, Divyam Rastogi, Oliver Brock
mathjax: true
---

* content
{:toc}

##### Abstract
We present differentiable particle filters (DPFs): a differentiable implementation of the particle filter algorithm with learnable motion and measurement models. Since DPFs are end-to-end differentiable, we can efficiently train their models by optimizing end-to-end state estimation performance, rather than proxy objectives such as model accuracy. DPFs encode the structure of recursive state estimation with prediction and measurement update that operate on a probability distribution over states. This structure represents an algorithmic prior that improves learning performance in state estimation problems while enabling explainability of the learned model. Our experiments on simulated and real data show substantial benefits from end-to- end learning with algorithmic priors, e.g. reducing error rates by ~80%. Our experiments also show that, unlike long short-term memory networks, DPFs learn localization in a policy-agnostic way and thus greatly improve generalization. Source code is available at https://github.com/tu-rbo/differentiable-particle-filters.

##### Abstract (translated by Google)
我们提出可微分粒子滤波器（DPF）：粒子滤波器算法的可微分实现与可学习的运动和测量模型。由于DPF是端到端可区分的，我们可以通过优化端到端状态估计性能而非代理目标（如模型精度）来有效地训练其模型。 DPF使用预测和测量更新对递归状态估计的结构进行编码，所述预测和测量更新在状态上的概率分布上进行操作。这种结构代表了先前算法，提高了状态估计问题的学习性能，同时使学习模型具有可解释性。我们对模拟和真实数据的实验表明，使用算法先验的端到端学习具有很大的益处，例如，减少了〜80％的错误率。我们的实验还表明，与长期短期记忆网络不同，DPF通过与策略无关的方式学习本地化，从而大大提高了泛化能力。源代码位于https://github.com/tu-rbo/differentialable-particle-filters。

##### URL
[http://arxiv.org/abs/1805.11122](http://arxiv.org/abs/1805.11122)

##### PDF
[http://arxiv.org/pdf/1805.11122](http://arxiv.org/pdf/1805.11122)

