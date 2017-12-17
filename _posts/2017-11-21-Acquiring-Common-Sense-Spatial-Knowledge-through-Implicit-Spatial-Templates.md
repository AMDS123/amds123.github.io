---
layout: post
title: "Acquiring Common Sense Spatial Knowledge through Implicit Spatial Templates"
date: 2017-11-21 02:41:36
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding Prediction Relation
author: Guillem Collell, Luc Van Gool, Marie-Francine Moens
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial understanding is a fundamental problem with wide-reaching real-world applications. The representation of spatial knowledge is often modeled with spatial templates, i.e., regions of acceptability of two objects under an explicit spatial relationship (e.g., "on", "below", etc.). In contrast with prior work that restricts spatial templates to explicit spatial prepositions (e.g., "glass on table"), here we extend this concept to implicit spatial language, i.e., those relationships (generally actions) for which the spatial arrangement of the objects is only implicitly implied (e.g., "man riding horse"). In contrast with explicit relationships, predicting spatial arrangements from implicit spatial language requires significant common sense spatial understanding. Here, we introduce the task of predicting spatial templates for two objects under a relationship, which can be seen as a spatial question-answering task with a (2D) continuous output ("where is the man w.r.t. a horse when the man is walking the horse?"). We present two simple neural-based models that leverage annotated images and structured text to learn this task. The good performance of these models reveals that spatial locations are to a large extent predictable from implicit spatial language. Crucially, the models attain similar performance in a challenging generalized setting, where the object-relation-object combinations (e.g.,"man walking dog") have never been seen before. Next, we go one step further by presenting the models with unseen objects (e.g., "dog"). In this scenario, we show that leveraging word embeddings enables the models to output accurate spatial predictions, proving that the models acquire solid common sense spatial knowledge allowing for such generalization.

##### Abstract (translated by Google)
空间理解是具有广泛实际应用的基本问题。空间知识的表示通常用空间模板（即，在明确的空间关系（例如，“在...上”，“在...下面”等）下的两个对象的可接受性的区域）建模。与先前将空间模板限制为显式空间介词的工作（例如，“桌上玻璃”）相比，在这里我们将这个概念扩展到隐式空间语言，即对象的空间排列的那些关系只隐含暗示（例如“人骑马”）。与显式关系相反，从隐式空间语言预测空间安排需要重要的常识空间理解。在这里，我们介绍预测关系下的两个对象的空间模板的任务，这可以被看作是一个空间问题回答任务（2D）连续输出（“男人走路的时候，马？”）。我们提出两个简单的基于神经的模型，利用带注释的图像和结构化文本来学习这个任务。这些模型的良好性能表明空间位置在很大程度上可以从隐式空间语言预测。至关重要的是，这些模型在一个具有挑战性的广义设置中达到相似的性能，在这种设置中，对象 - 关系 - 对象组合（例如“人行狗”）从未见过。接下来，我们进一步通过展示具有看不见的对象（例如，“狗”）的模型。在这种情况下，我们表明，利用词嵌入使模型输出精确的空间预测，证明模型获得固体常识空间知识允许这种泛化。

##### URL
[https://arxiv.org/abs/1711.06821](https://arxiv.org/abs/1711.06821)

##### PDF
[https://arxiv.org/pdf/1711.06821](https://arxiv.org/pdf/1711.06821)

