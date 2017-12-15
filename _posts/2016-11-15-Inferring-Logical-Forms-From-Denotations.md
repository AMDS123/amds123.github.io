---
layout: post
title: "Inferring Logical Forms From Denotations"
date: 2016-11-15 21:24:08
categories: arXiv_CL
tags: arXiv_CL
author: Panupong Pasupat, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
A core problem in learning semantic parsers from denotations is picking out consistent logical forms--those that yield the correct denotation--from a combinatorially large space. To control the search space, previous work relied on restricted set of rules, which limits expressivity. In this paper, we consider a much more expressive class of logical forms, and show how to use dynamic programming to efficiently represent the complete set of consistent logical forms. Expressivity also introduces many more spurious logical forms which are consistent with the correct denotation but do not represent the meaning of the utterance. To address this, we generate fictitious worlds and use crowdsourced denotations on these worlds to filter out spurious logical forms. On the WikiTableQuestions dataset, we increase the coverage of answerable questions from 53.5% to 76%, and the additional crowdsourced supervision lets us rule out 92.1% of spurious logical forms.

##### Abstract (translated by Google)
从符号学习语义分析器的一个核心问题是从一个组合的大空间中挑选出一致的逻辑形式 - 那些产生正确的外延的逻辑形式。为了控制搜索空间，以前的工作依赖于限制表达规则的一套规则。在本文中，我们考虑了一个更具表现力的逻辑形式类，并展示了如何使用动态规划来高效地表示一整套一致的逻辑形式。表达式还引入了更多的虚假的逻辑形式，这些形式与正确的外延符合，但不代表话语的含义。为了解决这个问题，我们产生虚构的世界，并在这些世界上使用众包的指示来过滤虚假的逻辑形式。在WikiTableQuestions数据集中，我们将可回答问题的覆盖率从53.5％增加到76％，额外的众包监督让我们排除了92.1％的虚假逻辑形式。

##### URL
[https://arxiv.org/abs/1606.06900](https://arxiv.org/abs/1606.06900)

##### PDF
[https://arxiv.org/pdf/1606.06900](https://arxiv.org/pdf/1606.06900)

