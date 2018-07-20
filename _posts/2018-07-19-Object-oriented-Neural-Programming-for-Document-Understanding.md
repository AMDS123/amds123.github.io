---
layout: post
title: "Object-oriented Neural Programming for Document Understanding"
date: 2018-07-19 11:21:07
categories: arXiv_AI
tags: arXiv_AI Ontology Reinforcement_Learning
author: Zhengdong Lu, Haotian Cui, Xianggen Liu, Yukun Yan, Daqi Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Object-oriented Neural Programming (OONP), a framework for semantically parsing documents in specific domains. Basically, OONP reads a document and parses it into a predesigned object-oriented data structure (referred to as ontology in this paper) that reflects the domain-specific semantics of the document. An OONP parser models semantic parsing as a decision process: a neural net-based Reader sequentially goes through the document, and during the process it builds and updates an intermediate ontology to summarize its partial understanding of the text it covers. OONP supports a rich family of operations (both symbolic and differentiable) for composing the ontology, and a big variety of forms (both symbolic and differentiable) for representing the state and the document. An OONP parser can be trained with supervision of different forms and strength, including supervised learning (SL) , reinforcement learning (RL) and hybrid of the two. Our experiments on both synthetic and real-world document parsing tasks have shown that OONP can learn to handle fairly complicated ontology with training data of modest sizes.

##### Abstract (translated by Google)
我们提出了面向对象的神经规划（OONP），一种用于语义解析特定域中的文档的框架。基本上，OONP读取文档并将其解析为预先设计的面向对象的数据结构（本文中称为本体），它反映了文档的特定于域的语义。 OONP解析器将语义解析建模为决策过程：基于神经网络的读取器按顺序遍历文档，在此过程中，它构建并更新中间本体，以总结其对所涵盖文本的部分理解。 OONP支持用于组成本体的丰富操作系列（符号和可微分），以及用于表示状态和文档的各种形式（符号和可区分）。 OONP解析器可以通过不同形式和强度的监督进行训练，包括监督学习（SL），强化学习（RL）和两者的混合。我们对合成和现实文档解析任务的实验表明，OONP可以学习处理相当复杂的本体，并且训练数据适中。

##### URL
[http://arxiv.org/abs/1709.08853](http://arxiv.org/abs/1709.08853)

##### PDF
[http://arxiv.org/pdf/1709.08853](http://arxiv.org/pdf/1709.08853)

