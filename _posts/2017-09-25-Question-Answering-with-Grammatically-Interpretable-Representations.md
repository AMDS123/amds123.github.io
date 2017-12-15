---
layout: post
title: "Question-Answering with Grammatically-Interpretable Representations"
date: 2017-09-25 23:49:18
categories: arXiv_CL
tags: arXiv_CL Knowledge QA Attention Optimization
author: Hamid Palangi, Paul Smolensky, Xiaodong He, Li Deng
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an architecture, the Tensor Product Recurrent Network (TPRN). In our application of TPRN, internal representations learned by end-to-end optimization in a deep neural network performing a textual question-answering (QA) task can be interpreted using basic concepts from linguistic theory. No performance penalty need be paid for this increased interpretability: the proposed model performs comparably to a state-of-the-art system on the SQuAD QA task. The internal representation which is interpreted is a Tensor Product Representation: for each input word, the model selects a symbol to encode the word, and a role in which to place the symbol, and binds the two together. The selection is via soft attention. The overall interpretation is built from interpretations of the symbols, as recruited by the trained model, and interpretations of the roles as used by the model. We find support for our initial hypothesis that symbols can be interpreted as lexical-semantic word meanings, while roles can be interpreted as approximations of grammatical roles (or categories) such as subject, wh-word, determiner, etc. Fine-grained analysis reveals specific correspondences between the learned roles and parts of speech as assigned by a standard tagger (Toutanova et al. 2003), and finds several discrepancies in the model's favor. In this sense, the model learns significant aspects of grammar, after having been exposed solely to linguistically unannotated text, questions, and answers: no prior linguistic knowledge is given to the model. What is given is the means to build representations using symbols and roles, with an inductive bias favoring use of these in an approximately discrete manner.

##### Abstract (translated by Google)
我们介绍一个架构，张量产品递归网络（TPRN）。在我们对TPRN的应用中，在深度神经网络中进行文本问答（QA）任务时，通过端到端优化学习到的内部表示可以使用语言理论的基本概念来解释。对于这种提高的可解释性，不需要付出任何性能损失：所提出的模型与SQUAD QA任务中的最先进的系统性能相当。被解释的内部表示是一个张量乘积表示：对于每个输入单词，模型选择一个符号来编码单词，以及放置符号的角色，并将两者结合在一起。选择是通过软性的关注。整体解释是根据经过训练的模型所招募的符号的解释以及模型所使用的角色的解释而构建的。我们发现支持我们最初的假设，即符号可以被解释为词汇 - 语义词的意义，而角色可以被解释为语法角色（或类别）的近似，例如主语，wh-词，确定词等。细粒度分析揭示（Toutanova et al。2003）指定的学习角色和言语部分之间的特定对应关系，并发现模型有利的几个差异。从这个意义上说，这个模型在仅仅暴露于语言无法理解的文本，问题和答案之后，学习了语法的重要方面：没有先前的语言知识被赋予模型。所给出的是用符号和角色来建立表示的方法，并且以一种近似离散的方式来利用这些表示。

##### URL
[https://arxiv.org/abs/1705.08432](https://arxiv.org/abs/1705.08432)

##### PDF
[https://arxiv.org/pdf/1705.08432](https://arxiv.org/pdf/1705.08432)

