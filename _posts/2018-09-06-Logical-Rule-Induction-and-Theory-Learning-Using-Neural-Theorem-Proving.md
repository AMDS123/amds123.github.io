---
layout: post
title: "Logical Rule Induction and Theory Learning Using Neural Theorem Proving"
date: 2018-09-06 19:49:20
categories: arXiv_AI
tags: arXiv_AI Inference
author: Andres Campero, Aldo Pareja, Tim Klinger, Josh Tenenbaum, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
A hallmark of human cognition is the ability to continually acquire and distill observations of the world into meaningful, predictive theories. In this paper we present a new mechanism for logical theory acquisition which takes a set of observed facts and learns to extract from them a set of logical rules and a small set of core facts which together entail the observations. Our approach is neuro-symbolic in the sense that the rule pred- icates and core facts are given dense vector representations. The rules are applied to the core facts using a soft unification procedure to infer additional facts. After k steps of forward inference, the consequences are compared to the initial observations and the rules and core facts are then encouraged towards representations that more faithfully generate the observations through inference. Our approach is based on a novel neural forward-chaining differentiable rule induction network. The rules are interpretable and learned compositionally from their predicates, which may be invented. We demonstrate the efficacy of our approach on a variety of ILP rule induction and domain theory learning datasets.

##### Abstract (translated by Google)
人类认知的一个标志是能够不断获取和提取世界观察到有意义的预测理论。在本文中，我们提出了一种新的逻辑理论获取机制，它采用一组观察到的事实并学习从中提取一组逻辑规则和一小组核心事实，这些事实共同构成了观察。我们的方法是神经象征性的，因为规则预测和核心事实被赋予密集的向量表示。这些规则适用于核心事实，使用软统一程序来推断其他事实。在前进推理的k步之后，将后果与初始观察结果进行比较，然后鼓励规则和核心事实通过推理更忠实地产生观察的表示。我们的方法基于一种新颖的神经前向链可微分规则归纳网络。这些规则可以从其谓词中进行解释和学习，这些谓词可以被发明。我们证明了我们的方法对各种ILP规则归纳和领域理论学习数据集的有效性。

##### URL
[http://arxiv.org/abs/1809.02193](http://arxiv.org/abs/1809.02193)

##### PDF
[http://arxiv.org/pdf/1809.02193](http://arxiv.org/pdf/1809.02193)

