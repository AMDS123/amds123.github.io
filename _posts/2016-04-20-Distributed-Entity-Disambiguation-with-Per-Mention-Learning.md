---
layout: post
title: "Distributed Entity Disambiguation with Per-Mention Learning"
date: 2016-04-20 09:53:42
categories: arXiv_SD
tags: arXiv_SD Knowledge
author: Tiep Mai, Bichen Shi, Patrick K. Nicholson, Deepak Ajwani, Alessandra Sala
mathjax: true
---

* content
{:toc}

##### Abstract
Entity disambiguation, or mapping a phrase to its canonical representation in a knowledge base, is a fundamental step in many natural language processing applications. Existing techniques based on global ranking models fail to capture the individual peculiarities of the words and hence, either struggle to meet the accuracy requirements of many real-world applications or they are too complex to satisfy real-time constraints of applications. In this paper, we propose a new disambiguation system that learns specialized features and models for disambiguating each ambiguous phrase in the English language. To train and validate the hundreds of thousands of learning models for this purpose, we use a Wikipedia hyperlink dataset with more than 170 million labelled annotations. We provide an extensive experimental evaluation to show that the accuracy of our approach compares favourably with respect to many state-of-the-art disambiguation systems. The training required for our approach can be easily distributed over a cluster. Furthermore, updating our system for new entities or calibrating it for special ones is a computationally fast process, that does not affect the disambiguation of the other entities.

##### Abstract (translated by Google)
在许多自然语言处理应用程序中，实体消除歧义或将短语映射到其规范表示形式是知识库中的一个基本步骤。基于全局排序模型的现有技术未能捕捉到单词的个别特征，因此无法满足许多实际应用的精度要求，或者它们太复杂以至于不能满足应用的实时限制。在本文中，我们提出了一个新的消歧系统，学习用于歧义歧义在英语的每个含糊不清的短语的专业特点和模型。为了训练和验证数十万种用于此目的的学习模型，我们使用了一个拥有超过1.7亿标注注释的维基百科超链接数据集。我们提供了一个广泛的实验评估，以表明我们的方法的准确性比许多最先进的消歧系统有利。我们的方法所需的培训可以很容易地分布在一个集群上。此外，更新我们的新实体系统或为特定实体进行校准是一个计算快速的过程，不会影响其他实体的消歧。

##### URL
[https://arxiv.org/abs/1604.05875](https://arxiv.org/abs/1604.05875)

##### PDF
[https://arxiv.org/pdf/1604.05875](https://arxiv.org/pdf/1604.05875)

