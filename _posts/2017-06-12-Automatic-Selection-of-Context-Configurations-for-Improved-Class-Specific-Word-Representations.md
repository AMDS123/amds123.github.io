---
layout: post
title: "Automatic Selection of Context Configurations for Improved Class-Specific Word Representations"
date: 2017-06-12 13:11:53
categories: arXiv_CL
tags: arXiv_CL Relation
author: Ivan Vulić, Roy Schwartz, Ari Rappoport, Roi Reichart, Anna Korhonen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is concerned with identifying contexts useful for training word representation models for different word classes such as adjectives (A), verbs (V), and nouns (N). We introduce a simple yet effective framework for an automatic selection of class-specific context configurations. We construct a context configuration space based on universal dependency relations between words, and efficiently search this space with an adapted beam search algorithm. In word similarity tasks for each word class, we show that our framework is both effective and efficient. Particularly, it improves the Spearman's rho correlation with human scores on SimLex-999 over the best previously proposed class-specific contexts by 6 (A), 6 (V) and 5 (N) rho points. With our selected context configurations, we train on only 14% (A), 26.2% (V), and 33.6% (N) of all dependency-based contexts, resulting in a reduced training time. Our results generalise: we show that the configurations our algorithm learns for one English training setup outperform previously proposed context types in another training setup for English. Moreover, basing the configuration space on universal dependencies, it is possible to transfer the learned configurations to German and Italian. We also demonstrate improved per-class results over other context types in these two languages.

##### Abstract (translated by Google)
本文关注于识别用于训练不同词类（例如形容词（A），动词（V）和名词（N））的词表示模型的上下文。我们引入了一个简单而有效的框架来自动选择类特定的上下文配置。我们基于单词之间的通用依赖关系来构造上下文配置空间，并且使用适合的波束搜索算法来有效地搜索这个空间。在每个单词类的单词相似性任务中，我们展示了我们的框架既有效又高效。特别地，它通过6（A），6（V）和5（N）rho点在先前提出的最佳类别上下文中改善了SimLex-999上Spearman's rho与人类分数的相关性。使用我们选择的上下文配置，我们只训练所有依赖情境的14％（A），26.2％（V）和33.6％（N），从而缩短训练时间。我们的结果总结：我们表明，我们的算法学习一个英语训练设置的配置要胜过以前提出的在另一个英语训练设置中的上下文类型。而且，将配置空间建立在通用依赖的基础上，可以将学习的配置转换为德语和意大利语。在这两种语言中，我们还演示了比其他上下文类型更好的每类结果。

##### URL
[https://arxiv.org/abs/1608.05528](https://arxiv.org/abs/1608.05528)

##### PDF
[https://arxiv.org/pdf/1608.05528](https://arxiv.org/pdf/1608.05528)

