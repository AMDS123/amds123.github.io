---
layout: post
title: 'Automatically Generating Commit Messages from Diffs using Neural Machine Translation'
date: 2017-08-30 22:26:48
categories: arXiv_CL
tags: arXiv_CL NMT
author: Siyuan Jiang, Ameer Armaly, Collin McMillan
---

* content
{:toc}

##### Abstract
Commit messages are a valuable resource in comprehension of software evolution, since they provide a record of changes such as feature additions and bug repairs. Unfortunately, programmers often neglect to write good commit messages. Different techniques have been proposed to help programmers by automatically writing these messages. These techniques are effective at describing what changed, but are often verbose and lack context for understanding the rationale behind a change. In contrast, humans write messages that are short and summarize the high level rationale. In this paper, we adapt Neural Machine Translation (NMT) to automatically "translate" diffs into commit messages. We trained an NMT algorithm using a corpus of diffs and human-written commit messages from the top 1k Github projects. We designed a filter to help ensure that we only trained the algorithm on higher-quality commit messages. Our evaluation uncovered a pattern in which the messages we generate tend to be either very high or very low quality. Therefore, we created a quality-assurance filter to detect cases in which we are unable to produce good messages, and return a warning instead.

##### Abstract (translated by Google)
提交消息是理解软件演变的宝贵资源，因为它们提供了诸如功能添加和错误修复等变化的记录。不幸的是，程序员往往忽视写好的提交信息。已经提出了不同的技术来通过自动编写这些消息来帮助程序员。这些技术在描述变化的原理上是有效的，但是往往是冗长的，缺乏理解变化背后原理的背景。相比之下，人类写短的信息，并总结高层次的理由。在本文中，我们使用神经机器翻译（NMT）来自动将差异“翻译”为提交消息。我们使用来自顶级1k Github项目的差异语料库和人工编写的提交消息来训练NMT算法。我们设计了一个过滤器来帮助确保我们只在更高质量的提交消息上训练算法。我们的评估发现了一个模式，我们所产生的信息往往是非常高或非常低的质量。因此，我们创建了质量保证过滤器来检测无法生成好消息的情况，并返回警告。

##### URL
[https://arxiv.org/abs/1708.09492](https://arxiv.org/abs/1708.09492)

