---
layout: post
title: "Deep Probabilistic Logic: A Unifying Framework for Indirect Supervision"
date: 2018-08-26 00:02:36
categories: arXiv_CL
tags: arXiv_CL Knowledge Represenation_Learning Inference Deep_Learning Relation
author: Hai Wang, Hoifung Poon
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has emerged as a versatile tool for a wide range of NLP tasks, due to its superior capacity in representation learning. But its applicability is limited by the reliance on annotated examples, which are difficult to produce at scale. Indirect supervision has emerged as a promising direction to address this bottleneck, either by introducing labeling functions to automatically generate noisy examples from unlabeled text, or by imposing constraints over interdependent label decisions. A plethora of methods have been proposed, each with respective strengths and limitations. Probabilistic logic offers a unifying language to represent indirect supervision, but end-to-end modeling with probabilistic logic is often infeasible due to intractable inference and learning. In this paper, we propose deep probabilistic logic (DPL) as a general framework for indirect supervision, by composing probabilistic logic with deep learning. DPL models label decisions as latent variables, represents prior knowledge on their relations using weighted first-order logical formulas, and alternates between learning a deep neural network for the end task and refining uncertain formula weights for indirect supervision, using variational EM. This framework subsumes prior indirect supervision methods as special cases, and enables novel combination via infusion of rich domain and linguistic knowledge. Experiments on biomedical machine reading demonstrate the promise of this approach.

##### Abstract (translated by Google)
由于其卓越的表现学习能力，深度学习已成为各种NLP任务的多功能工具。但是它的适用性受到对注释实例的依赖的限制，这些实例难以大规模生产。间接监督已经成为解决这一瓶颈的有希望的方向，要么通过引入标签功能来自动生成来自未标记文本的嘈杂示例，要么通过对相互依赖的标签决策施加约束。已经提出了许多方法，每种方法都有各自的优点和局限性。概率逻辑提供了一种统一的语言来表示间接监督，但由于难以理解的推理和学习，使用概率逻辑的端到端建模通常是不可行的。在本文中，我们通过深度学习组合概率逻辑，提出深度概率逻辑（DPL）作为间接监督的一般框架。 DPL模型将决策标记为潜在变量，使用加权一阶逻辑公式表示其关系的先验知识，并且使用变分EM在为最终任务学习深度神经网络和为间接监督精炼不确定公式权重之间交替。该框架将先前的间接监督方法作为特殊情况包含在内，并通过输入丰富的领域和语言知识实现新颖的组合。生物医学机器阅读的实验证明了这种方法的前景。

##### URL
[http://arxiv.org/abs/1808.08485](http://arxiv.org/abs/1808.08485)

##### PDF
[http://arxiv.org/pdf/1808.08485](http://arxiv.org/pdf/1808.08485)

