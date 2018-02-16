---
layout: post
title: "Mapping Images to Scene Graphs with Permutation-Invariant Structured Prediction"
date: 2018-02-15 09:50:15
categories: arXiv_CV
tags: arXiv_CV Prediction Relation
author: Roei Herzig, Moshiko Raboh, Gal Chechik, Jonathan Berant, Amir Globerson
mathjax: true
---

* content
{:toc}

##### Abstract
Structured prediction is concerned with predicting multiple inter-dependent labels simultaneously. Classical methods like CRF achieve this by maximizing a score function over the set of possible label assignments. Recent extensions use neural networks to either implement the score function or in maximization. The current paper takes an alternative approach, using a neural network to generate the structured output directly, without going through a score function. We take an axiomatic perspective to derive the desired properties and invariances of a such network to certain input permutations, presenting a structural characterization that is provably both necessary and sufficient. We then discuss graph-permutation invariant (GPI) architectures that satisfy this characterization and explain how they can be used for deep structured prediction. We evaluate our approach on the challenging problem of inferring a {\em scene graph} from an image, namely, predicting entities and their relations in the image. We obtain state-of-the-art results on the challenging Visual Genome benchmark, outperforming all recent approaches.

##### Abstract (translated by Google)
结构化预测涉及同时预测多个相互依赖的标签。像CRF这样的经典方法通过在可能的标签分配集上最大化分数函数来实现这一点。最近的扩展使用神经网络来实现分数函数或最大化。当前的论文采用了另一种方法，即使用神经网络直接生成结构化输出，而不需要通过分数函数。我们从公理角度出发，将某个网络的期望特性和不变性推导到某些输入变换中，从而提供一个可证明的必要和充分的结构特征。然后我们讨论满足此特征的图 - 置换不变（GPI）架构，并解释它们如何用于深层结构预测。我们评估我们的方法在从图像推断{\ em场景图}的挑战性问题上，即预测图像中的实体及其关系。我们在具有挑战性的Visual Genome基准测试中获得了最新的结果，超越了所有最新的方法。

##### URL
[https://arxiv.org/abs/1802.05451](https://arxiv.org/abs/1802.05451)

##### PDF
[https://arxiv.org/pdf/1802.05451](https://arxiv.org/pdf/1802.05451)

