---
layout: post
title: "DeepType: Multilingual Entity Linking by Neural Type System Evolution"
date: 2018-02-03 20:13:42
categories: arXiv_CL
tags: arXiv_CL Ontology Embedding Optimization Deep_Learning Gradient_Descent Relation
author: Jonathan Raiman, Olivier Raiman
mathjax: true
---

* content
{:toc}

##### Abstract
The wealth of structured (e.g. Wikidata) and unstructured data about the world available today presents an incredible opportunity for tomorrow's Artificial Intelligence. So far, integration of these two different modalities is a difficult process, involving many decisions concerning how best to represent the information so that it will be captured or useful, and hand-labeling large amounts of data. DeepType overcomes this challenge by explicitly integrating symbolic information into the reasoning process of a neural network with a type system. First we construct a type system, and second, we use it to constrain the outputs of a neural network to respect the symbolic structure. We achieve this by reformulating the design problem into a mixed integer problem: create a type system and subsequently train a neural network with it. In this reformulation discrete variables select which parent-child relations from an ontology are types within the type system, while continuous variables control a classifier fit to the type system. The original problem cannot be solved exactly, so we propose a 2-step algorithm: 1) heuristic search or stochastic optimization over discrete variables that define a type system informed by an Oracle and a Learnability heuristic, 2) gradient descent to fit classifier parameters. We apply DeepType to the problem of Entity Linking on three standard datasets (i.e. WikiDisamb30, CoNLL (YAGO), TAC KBP 2010) and find that it outperforms all existing solutions by a wide margin, including approaches that rely on a human-designed type system or recent deep learning-based entity embeddings, while explicitly using symbolic information lets it integrate new entities without retraining.

##### Abstract (translated by Google)
今天的世界上有组织的（如Wikidata）和非结构化数据的财富为明天的人工智能提供了一个难以置信的机会。到目前为止，这两种不同形式的整合是一个困难的过程，涉及许多关于如何最好地表示信息以使其被捕获或有用的决定，以及手工标记大量数据的决定。 DeepType通过将符号信息显式集成到具有类型系统的神经网络的推理过程中来克服这个挑战。首先我们构造一个类型系统，其次，我们用它来约束神经网络的输出来尊重符号结构。我们通过将设计问题重新构造成一个混合整数问题来实现这个目的：创建一个类型系统，并随后用它来训练一个神经网络。在这个重新构造中，离散变量选择来自本体的哪些亲子关系是类型系统内的类型，而连续变量则控制适合类型系统的分类器。所以我们提出了一个两步算法：1）启发式搜索或随机优化离散变量，定义由Oracle通知的类型系统和Learnability启发式，2）梯度下降以适应分类器参数。我们将DeepType应用于三个标准数据集（即WikiDisamb30，CoNLL（YAGO），TAC KBP 2010）上的实体链接问题，并发现它在很大程度上优于所有现有的解决方案，包括依赖于人类设计类型系统或者最近深入的基于学习的实体嵌入，而明确地使用符号信息则可以在不进行再培训的情况下整合新的实体。

##### URL
[http://arxiv.org/abs/1802.01021](http://arxiv.org/abs/1802.01021)

##### PDF
[http://arxiv.org/pdf/1802.01021](http://arxiv.org/pdf/1802.01021)

