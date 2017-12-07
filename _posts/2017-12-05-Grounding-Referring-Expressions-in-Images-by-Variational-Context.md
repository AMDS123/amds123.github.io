---
layout: post
title: "Grounding Referring Expressions in Images by Variational Context"
date: 2017-12-05 19:57:52
categories: arXiv_CV
tags: arXiv_CV Embedding Relation
author: Hanwang Zhang, Yulei Niu, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on grounding (i.e., localizing or linking) referring expressions in images, e.g., "largest elephant standing behind baby elephant". This is a general yet challenging vision-language task since it does not only require the localization of objects, but also the multimodal comprehension of context --- visual attributes (e.g., "largest", "baby") and relationships (e.g., "behind") that help to distinguish the referent from other objects, especially those of the same category. Due to the exponential complexity involved in modeling the context associated with multiple image regions, existing work oversimplifies this task to pairwise region modeling by multiple instance learning. In this paper, we propose a variational Bayesian method, called Variational Context, to solve the problem of complex context modeling in referring expression grounding. Our model exploits the reciprocal relation between the referent and context, i.e., either of them influences the estimation of the posterior distribution of the other, and thereby the search space of context can be greatly reduced, resulting in better localization of referent. We develop a novel cue-specific language-vision embedding network that learns this reciprocity model end-to-end. We also extend the model to the unsupervised setting where no annotation for the referent is available. Extensive experiments on various benchmarks show consistent improvement over state-of-the-art methods in both supervised and unsupervised settings.

##### Abstract (translated by Google)
我们专注于在图像中引用表达（例如，“站在小象后面的最大的象”）的基础（即，本地化或链接）。这是一个普遍而又具有挑战性的视觉语言任务，因为它不仅需要对象的本地化，而且还需要对语境的多模式理解---视觉属性（例如“最大”，“宝贝”）和关系（例如“后面“），这有助于将指代物与其他物体（特别是同类物体）区分开来。由于与多个图像区域相关联的上下文建模涉及指数复杂性，所以现有工作将该任务简化为通过多实例学习进行的成对区域建模。在本文中，我们提出了一种称为变分上下文的变分贝叶斯方法来解决表达式接地中的复杂上下文建模问题。我们的模型利用了指称与上下文之间的相互关系，也就是说，它们都影响着对方的后验分布的估计，从而可以大大减少上下文的搜索空间，从而更好地定位指示对象。我们开发了一种新的提示特定的语言视觉嵌入网络，学习这种互惠模型的端到端。我们还将模型扩展到无监督设置，其中不存在对象的注释可用。在各种基准上进行的大量实验显示，在有监督和无监督的情况下，都比最先进的方法持续改进。

##### URL
[http://arxiv.org/abs/1712.01892](http://arxiv.org/abs/1712.01892)

##### PDF
[http://arxiv.org/pdf/1712.01892](http://arxiv.org/pdf/1712.01892)

