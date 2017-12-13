---
layout: post
title: "Dynamic Key-Value Memory Networks for Knowledge Tracing"
date: 2017-02-17 06:09:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Relation Memory_Networks
author: Jiani Zhang, Xingjian Shi, Irwin King, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge Tracing (KT) is a task of tracing evolving knowledge state of students with respect to one or more concepts as they engage in a sequence of learning activities. One important purpose of KT is to personalize the practice sequence to help students learn knowledge concepts efficiently. However, existing methods such as Bayesian Knowledge Tracing and Deep Knowledge Tracing either model knowledge state for each predefined concept separately or fail to pinpoint exactly which concepts a student is good at or unfamiliar with. To solve these problems, this work introduces a new model called Dynamic Key-Value Memory Networks (DKVMN) that can exploit the relationships between underlying concepts and directly output a student's mastery level of each concept. Unlike standard memory-augmented neural networks that facilitate a single memory matrix or two static memory matrices, our model has one static matrix called key, which stores the knowledge concepts and the other dynamic matrix called value, which stores and updates the mastery levels of corresponding concepts. Experiments show that our model consistently outperforms the state-of-the-art model in a range of KT datasets. Moreover, the DKVMN model can automatically discover underlying concepts of exercises typically performed by human annotations and depict the changing knowledge state of a student.

##### Abstract (translated by Google)
知识追踪（KT）是追踪学生在一系列学习活动中涉及一个或多个概念的不断变化的知识状态的任务。 KT的一个重要目的是个性化的练习顺序，帮助学生有效地学习知识概念。然而，贝叶斯知识追踪和深度知识追踪等现有方法要么单独为每个预定义的概念建立知识状态模型，要么无法精确地确定学生擅长或不熟悉的概念。为了解决这些问题，本文引入了一种新型的动态键值存储网络（Dynamic Key-Value Memory Networks，DKVMN），可以利用底层概念之间的关系，直接输出学生对每个概念的掌握程度。与标准的内存增强神经网络不同，后者有利于单个内存矩阵或两个静态内存矩阵，我们的模型有一个叫做key的静态矩阵，它存储知识概念和另一个叫做value的动态矩阵，它存储和更新相应的掌握级别概念。实验表明，我们的模型在一系列KT数据集中始终优于最先进的模型。此外，DKVMN模型可以自动发现通常由人类注释执行的练习的基本概念，并描绘学生不断变化的知识状态。

##### URL
[https://arxiv.org/abs/1611.08108](https://arxiv.org/abs/1611.08108)

##### PDF
[https://arxiv.org/pdf/1611.08108](https://arxiv.org/pdf/1611.08108)

