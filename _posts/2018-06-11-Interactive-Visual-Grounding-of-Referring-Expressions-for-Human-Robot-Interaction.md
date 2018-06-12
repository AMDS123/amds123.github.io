---
layout: post
title: "Interactive Visual Grounding of Referring Expressions for Human-Robot Interaction"
date: 2018-06-11 06:58:19
categories: arXiv_CV
tags: arXiv_CV Relation
author: Mohit Shridhar, David Hsu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents INGRESS, a robot system that follows human natural language instructions to pick and place everyday objects. The core issue here is the grounding of referring expressions: infer objects and their relationships from input images and language expressions. INGRESS allows for unconstrained object categories and unconstrained language expressions. Further, it asks questions to disambiguate referring expressions interactively. To achieve these, we take the approach of grounding by generation and propose a two-stage neural network model for grounding. The first stage uses a neural network to generate visual descriptions of objects, compares them with the input language expression, and identifies a set of candidate objects. The second stage uses another neural network to examine all pairwise relations between the candidates and infers the most likely referred object. The same neural networks are used for both grounding and question generation for disambiguation. Experiments show that INGRESS outperformed a state-of-the-art method on the RefCOCO dataset and in robot experiments with humans.

##### Abstract (translated by Google)
本文介绍了INGRESS，一种遵循人类自然语言指令来拾取和放置日常物体的机器人系统。这里的核心问题是引用表达式的基础：从输入图像和语言表达式推断对象及其关系。 INGRESS允许无约束的对象类别和无约束的语言表达式。此外，它会提出问题以交互方式消除引用表达式的歧义。为了实现这些目标，我们采用了基于代的接地方法，并提出了一个两阶段的接地神经网络模型。第一阶段使用神经网络生成对象的可视化描述，将它们与输入语言表达式进行比较，并识别一组候选对象。第二阶段使用另一个神经网络来检查候选人之间的所有配对关系，并推断出最可能被引用的对象。同样的神经网络用于消歧的接地和问题生成。实验表明，INGRESS在RefCOCO数据集和机器人对人类的实验中胜过了最先进的方法。

##### URL
[http://arxiv.org/abs/1806.03831](http://arxiv.org/abs/1806.03831)

##### PDF
[http://arxiv.org/pdf/1806.03831](http://arxiv.org/pdf/1806.03831)

