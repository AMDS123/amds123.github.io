---
layout: post
title: "Markov Logic Networks for Natural Language Question Answering"
date: 2015-07-10 23:17:53
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: Tushar Khot, Niranjan Balasubramanian, Eric Gribkoff, Ashish Sabharwal, Peter Clark, Oren Etzioni
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal is to answer elementary-level science questions using knowledge extracted automatically from science textbooks, expressed in a subset of first-order logic. Given the incomplete and noisy nature of these automatically extracted rules, Markov Logic Networks (MLNs) seem a natural model to use, but the exact way of leveraging MLNs is by no means obvious. We investigate three ways of applying MLNs to our task. In the first, we simply use the extracted science rules directly as MLN clauses. Unlike typical MLN applications, our domain has long and complex rules, leading to an unmanageable number of groundings. We exploit the structure present in hard constraints to improve tractability, but the formulation remains ineffective. In the second approach, we instead interpret science rules as describing prototypical entities, thus mapping rules directly to grounded MLN assertions, whose constants are then clustered using existing entity resolution methods. This drastically simplifies the network, but still suffers from brittleness. Finally, our third approach, called Praline, uses MLNs to align the lexical elements as well as define and control how inference should be performed in this task. Our experiments, demonstrating a 15\% accuracy boost and a 10x reduction in runtime, suggest that the flexibility and different inference semantics of Praline are a better fit for the natural language question answering task.

##### Abstract (translated by Google)
我们的目标是使用从科学教科书中自动提取的知识来回答初等科学问题，用一阶逻辑的子集表示。鉴于这些自动提取规则的不完整和嘈杂的性质，马尔可夫逻辑网络（MLNs）似乎是一个自然的模型，但是利用MLN的确切方式并不明显。我们调查了三种应用MLN的方法来完成我们的任务。首先，我们直接使用提取的科学规则作为MLN子句。与典型的MLN应用程序不同，我们的领域有着漫长而复杂的规则，导致难以处理的数量。我们利用硬约束条件下的结构来改善易处理性，但是这个表述仍然是无效的。在第二种方法中，我们将科学规则解释为描述原型实体，从而将规则直接映射到基础的MLN断言，然后使用现有的实体解析方法对常量进行聚类。这大大简化了网络，但仍然脆弱。最后，我们的第三种方法叫做Praline，它使用MLN来调整词汇元素，并且定义和控制在这个任务中如何进行推理。我们的实验表明，15％的精度提升和10倍的运行时间缩短表明，果仁糖的灵活性和不同的推理语义更适合于自然语言问题的解答任务。

##### URL
[https://arxiv.org/abs/1507.03045](https://arxiv.org/abs/1507.03045)

##### PDF
[https://arxiv.org/pdf/1507.03045](https://arxiv.org/pdf/1507.03045)

