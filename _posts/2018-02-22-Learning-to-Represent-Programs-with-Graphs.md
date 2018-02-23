---
layout: post
title: "Learning to Represent Programs with Graphs"
date: 2018-02-22 11:59:03
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Miltiadis Allamanis, Marc Brockschmidt, Mahmoud Khademi
mathjax: true
---

* content
{:toc}

##### Abstract
Learning tasks on source code (i.e., formal languages) have been considered recently, but most work has tried to transfer natural language methods and does not capitalize on the unique opportunities offered by code's known syntax. For example, long-range dependencies induced by using the same variable or function in distant locations are often not considered. We propose to use graphs to represent both the syntactic and semantic structure of code and use graph-based deep learning methods to learn to reason over program structures. 
 In this work, we present how to construct graphs from source code and how to scale Gated Graph Neural Networks training to such large graphs. We evaluate our method on two tasks: VarNaming, in which a network attempts to predict the name of a variable given its usage, and VarMisuse, in which the network learns to reason about selecting the correct variable that should be used at a given program location. Our comparison to methods that use less structured program representations shows the advantages of modeling known structure, and suggests that our models learn to infer meaningful names and to solve the VarMisuse task in many cases. Additionally, our testing showed that VarMisuse identifies a number of bugs in mature open-source projects.

##### Abstract (translated by Google)
关于源代码（即正式语言）的学习任务最近已经被考虑过了，但大多数工作都试图转移自然语言方法，并且没有利用代码已知语法提供的独特机会。例如，通常不考虑在远处使用相同变量或函数引起的远程依赖性。我们建议使用图来表示代码的句法和语义结构，并使用基于图的深度学习方法来学习对程序结构进行推理。
 在这项工作中，我们将介绍如何从源代码构建图表，以及如何将门控图神经网络训练放大到如此大的图。我们在两项任务中评估我们的方法：VarNaming，其中一个网络试图根据其使用情况预测变量的名称; VarMisuse，网络学习如何选择在给定程序位置应使用的正确变量。我们与使用较少结构化程序表示的方法的比较显示了建模已知结构的优点，并且表明我们的模型学会推断有意义的名称并在许多情况下解决VarMisuse任务。另外，我们的测试表明VarMisuse在成熟的开源项目中发现了一些bug。

##### URL
[http://arxiv.org/abs/1711.00740](http://arxiv.org/abs/1711.00740)

##### PDF
[http://arxiv.org/pdf/1711.00740](http://arxiv.org/pdf/1711.00740)

