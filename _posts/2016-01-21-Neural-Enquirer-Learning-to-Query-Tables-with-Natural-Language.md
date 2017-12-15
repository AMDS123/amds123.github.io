---
layout: post
title: "Neural Enquirer: Learning to Query Tables with Natural Language"
date: 2016-01-21 02:46:25
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Gradient_Descent
author: Pengcheng Yin, Zhengdong Lu, Hang Li, Ben Kao
mathjax: true
---

* content
{:toc}

##### Abstract
We proposed Neural Enquirer as a neural network architecture to execute a natural language (NL) query on a knowledge-base (KB) for answers. Basically, Neural Enquirer finds the distributed representation of a query and then executes it on knowledge-base tables to obtain the answer as one of the values in the tables. Unlike similar efforts in end-to-end training of semantic parsers, Neural Enquirer is fully "neuralized": it not only gives distributional representation of the query and the knowledge-base, but also realizes the execution of compositional queries as a series of differentiable operations, with intermediate results (consisting of annotations of the tables at different levels) saved on multiple layers of memory. Neural Enquirer can be trained with gradient descent, with which not only the parameters of the controlling components and semantic parsing component, but also the embeddings of the tables and query words can be learned from scratch. The training can be done in an end-to-end fashion, but it can take stronger guidance, e.g., the step-by-step supervision for complicated queries, and benefit from it. Neural Enquirer is one step towards building neural network systems which seek to understand language by executing it on real-world. Our experiments show that Neural Enquirer can learn to execute fairly complicated NL queries on tables with rich structures.

##### Abstract (translated by Google)
我们提出了Neural Enquirer作为一个神经网络架构来执行自然语言（NL）查询知识库（KB）的答案。基本上，Neural Enquirer查找查询的分布式表示，然后在知识库表上执行它，以获得答案作为表中的一个值。不同于终端到终端的培训语义解析器的类似努力，神经询问者是完全“neuralized”：它不仅提供了查询和知识基础的分配体现，也是实现成分查询的执行一系列的微操作，中间结果（由不同级别的表格注释组成）保存在多层存储器中。神经元查询器可以用梯度下降法进行训练，不仅可以从头学习控制组件和语义解析组件的参数，还可以从头学习表和查询词的嵌入。培训可以以端到端的方式进行，但可以采取更强的指导，例如对复杂查询进行逐步监督，并从中受益。神经问题是建立神经网络系统的一个步骤，它试图通过在现实世界中执行语言来理解语言。我们的实验表明，Neural Enquirer可以学习在具有丰富结构的表上执行相当复杂的NL查询。

##### URL
[https://arxiv.org/abs/1512.00965](https://arxiv.org/abs/1512.00965)

##### PDF
[https://arxiv.org/pdf/1512.00965](https://arxiv.org/pdf/1512.00965)

