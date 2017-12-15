---
layout: post
title: "A Game-Theoretic Approach to Word Sense Disambiguation"
date: 2016-07-04 13:19:29
categories: arXiv_CL
tags: arXiv_CL Relation
author: Rocco Tripodi, Marcello Pelillo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new model for word sense disambiguation formulated in terms of evolutionary game theory, where each word to be disambiguated is represented as a node on a graph whose edges represent word relations and senses are represented as classes. The words simultaneously update their class membership preferences according to the senses that neighboring words are likely to choose. We use distributional information to weigh the influence that each word has on the decisions of the others and semantic similarity information to measure the strength of compatibility among the choices. With this information we can formulate the word sense disambiguation problem as a constraint satisfaction problem and solve it using tools derived from game theory, maintaining the textual coherence. The model is based on two ideas: similar words should be assigned to similar classes and the meaning of a word does not depend on all the words in a text but just on some of them. The paper provides an in-depth motivation of the idea of modeling the word sense disambiguation problem in terms of game theory, which is illustrated by an example. The conclusion presents an extensive analysis on the combination of similarity measures to use in the framework and a comparison with state-of-the-art systems. The results show that our model outperforms state-of-the-art algorithms and can be applied to different tasks and in different scenarios.

##### Abstract (translated by Google)
本文提出了一个新的词义消歧模型，以进化博弈理论为基础，将消歧的每个单词表示为一个图形上的一个节点，其边缘表示词关系，感官表示为类。这些词根据邻近词语可能选择的意义同时更新他们的班级成员偏好。我们使用分布信息来衡量每个词对他人决策的影响和语义相似度信息，以衡量选择之间的兼容性。利用这些信息，我们可以将感性消歧问题作为一个约束满足问题来形成，并使用来自博弈论的工具来解决问题，从而保持文本的连贯性。这个模式是基于两个观点：类似的词应该被分配到相似的类，一个词的意义不取决于一个文本中的所有单词，而只是其中的一些。本文从博弈论角度出发，提出了对词义消歧问题进行建模的思想，并以此为例进行深入探讨。结论对框架中使用的相似性度量的组合和与最先进的系统的比较进行了广泛的分析。结果表明，我们的模型胜过了最先进的算法，可以应用于不同的任务和不同的场景。

##### URL
[https://arxiv.org/abs/1606.07711](https://arxiv.org/abs/1606.07711)

##### PDF
[https://arxiv.org/pdf/1606.07711](https://arxiv.org/pdf/1606.07711)

