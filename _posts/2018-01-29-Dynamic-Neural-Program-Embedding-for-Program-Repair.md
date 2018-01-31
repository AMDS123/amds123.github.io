---
layout: post
title: "Dynamic Neural Program Embedding for Program Repair"
date: 2018-01-29 22:15:32
categories: arXiv_AI
tags: arXiv_AI Embedding RNN Prediction
author: Ke Wang, Rishabh Singh, Zhendong Su
mathjax: true
---

* content
{:toc}

##### Abstract
Neural program embeddings have shown much promise recently for a variety of program analysis tasks, including program synthesis, program repair, fault localization, etc. However, most existing program embeddings are based on syntactic features of programs, such as raw token sequences or abstract syntax trees. Unlike images and text, a program has an unambiguous semantic meaning that can be difficult to capture by only considering its syntax (i.e. syntactically similar pro- grams can exhibit vastly different run-time behavior), which makes syntax-based program embeddings fundamentally limited. This paper proposes a novel semantic program embedding that is learned from program execution traces. Our key insight is that program states expressed as sequential tuples of live variable values not only captures program semantics more precisely, but also offer a more natural fit for Recurrent Neural Networks to model. We evaluate different syntactic and semantic program embeddings on predicting the types of errors that students make in their submissions to an introductory programming class and two exercises on the CodeHunt education platform. Evaluation results show that our new semantic program embedding significantly outperforms the syntactic program embeddings based on token sequences and abstract syntax trees. In addition, we augment a search-based program repair system with the predictions obtained from our se- mantic embedding, and show that search efficiency is also significantly improved.

##### Abstract (translated by Google)
神经程序嵌入最近在许多程序分析任务（包括程序综合，程序修复，故障定位等）方面显示出许多希望。然而，大多数现有的程序嵌入基于程序的语法特征，例如原始标记序列或抽象语法树木。与图像和文本不同，程序具有明确的语义含义，仅仅考虑其语法就可能难以捕捉到（即句法上类似的程序可能表现出极大不同的运行时行为），这使得基于语法的程序嵌入受到根本性的限制。本文提出了一种从程序执行轨迹中学习的新颖的语义程序嵌入。我们的主要观点是，程序状态表示为活动变量值的连续元组，不仅更精确地捕捉程序语义，而且还为循环神经网络提供更自然的拟合模型。我们评估不同的句法和语义程序嵌入，以预测学生在提交给介绍性编程课的错误类型以及CodeHunt教育平台上的两个练习。评估结果表明，我们新的语义程序嵌入显着优于基于标记序列和抽象语法树的句法程序嵌入。另外，我们通过从我们的嵌入中获得的预测来增加一个基于搜索的程序修复系统，并且显示搜索效率也得到显着改善。

##### URL
[http://arxiv.org/abs/1711.07163](http://arxiv.org/abs/1711.07163)

##### PDF
[http://arxiv.org/pdf/1711.07163](http://arxiv.org/pdf/1711.07163)

