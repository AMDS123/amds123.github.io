---
layout: post
title: "Learning a Natural Language Interface with Neural Programmer"
date: 2017-03-02 16:02:00
categories: arXiv_CL
tags: arXiv_CL Knowledge Weakly_Supervised Face
author: Arvind Neelakantan, Quoc V. Le, Martin Abadi, Andrew McCallum, Dario Amodei
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a natural language interface for database tables is a challenging task that involves deep language understanding and multi-step reasoning. The task is often approached by mapping natural language queries to logical forms or programs that provide the desired response when executed on the database. To our knowledge, this paper presents the first weakly supervised, end-to-end neural network model to induce such programs on a real-world dataset. We enhance the objective function of Neural Programmer, a neural network with built-in discrete operations, and apply it on WikiTableQuestions, a natural language question-answering dataset. The model is trained end-to-end with weak supervision of question-answer pairs, and does not require domain-specific grammars, rules, or annotations that are key elements in previous approaches to program induction. The main experimental result in this paper is that a single Neural Programmer model achieves 34.2% accuracy using only 10,000 examples with weak supervision. An ensemble of 15 models, with a trivial combination technique, achieves 37.7% accuracy, which is competitive to the current state-of-the-art accuracy of 37.1% obtained by a traditional natural language semantic parser.

##### Abstract (translated by Google)
学习数据库表的自然语言接口是一项具有挑战性的任务，涉及深入的语言理解和多步推理。通常将自然语言查询映射为在数据库上执行时提供所需响应的逻辑表单或程序，从而处理任务。就我们所知，本文提出了第一个弱监督，端到端的神经网络模型，以在真实世界的数据集中引发这样的程序。我们增强了Neural Programmer（一种内置离散操作的神经网络）的目标函数，并将其应用于WikiTableQuestions（一种自然语言问答数据集）。该模型是端对端训练，对问题 - 答案对的监督较弱，并且不需要领域特定的语法，规则或注释，这些是先前编程归纳方法的关键元素。本文的主要实验结果是，一个神经程序员模型只使用了10,000个弱监督的例子，达到了34.2％的准确率。 15个模型的组合使用简单的组合技术，实现了37.7％的准确性，与传统的自然语言语义分析器获得的当前37.1％的最新准确度相当。

##### URL
[https://arxiv.org/abs/1611.08945](https://arxiv.org/abs/1611.08945)

##### PDF
[https://arxiv.org/pdf/1611.08945](https://arxiv.org/pdf/1611.08945)

