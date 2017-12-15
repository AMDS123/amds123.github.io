---
layout: post
title: "Neural Symbolic Machines: Learning Semantic Parsers on Freebase with Weak Supervision"
date: 2017-04-23 07:16:13
categories: arXiv_CL
tags: arXiv_CL Knowledge Prediction
author: Chen Liang, Jonathan Berant, Quoc Le, Kenneth D. Forbus, Ni Lao
mathjax: true
---

* content
{:toc}

##### Abstract
Harnessing the statistical power of neural networks to perform language understanding and symbolic reasoning is difficult, when it requires executing efficient discrete operations against a large knowledge-base. In this work, we introduce a Neural Symbolic Machine, which contains (a) a neural "programmer", i.e., a sequence-to-sequence model that maps language utterances to programs and utilizes a key-variable memory to handle compositionality (b) a symbolic "computer", i.e., a Lisp interpreter that performs program execution, and helps find good programs by pruning the search space. We apply REINFORCE to directly optimize the task reward of this structured prediction problem. To train with weak supervision and improve the stability of REINFORCE, we augment it with an iterative maximum-likelihood training process. NSM outperforms the state-of-the-art on the WebQuestionsSP dataset when trained from question-answer pairs only, without requiring any feature engineering or domain-specific knowledge.

##### Abstract (translated by Google)
当需要对大型知识库执行有效的离散操作时，利用神经网络的统计功能来执行语言理解和符号推理是困难的。在这项工作中，我们介绍一个神经符号机器，其中包含（a）一个神经“程序员”，即一个序列到序列的模型，将语言的发言映射到程序，并利用一个关键变量内存来处理组合性（b）一个象征性的“计算机”，即执行程序执行的Lisp解释器，通过修剪搜索空间来帮助找到好的程序。我们使用REINFORCE来直接优化这个结构化预测问题的任务奖励。为了训练弱监督和提高增强的稳定性，我们用一个迭代最大似然训练过程来增强它。 NSM比WebQuestionsSP数据集中的最新技术优于仅从问题 - 答案对进行训练，而不需要任何特征工程或领域特定的知识。

##### URL
[https://arxiv.org/abs/1611.00020](https://arxiv.org/abs/1611.00020)

##### PDF
[https://arxiv.org/pdf/1611.00020](https://arxiv.org/pdf/1611.00020)

