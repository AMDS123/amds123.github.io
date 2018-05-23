---
layout: post
title: "Depth-Limited Solving for Imperfect-Information Games"
date: 2018-05-21 17:41:32
categories: arXiv_AI
tags: arXiv_AI
author: Noam Brown, Tuomas Sandholm, Brandon Amos
mathjax: true
---

* content
{:toc}

##### Abstract
A fundamental challenge in imperfect-information games is that states do not have well-defined values. As a result, depth-limited search algorithms used in single-agent settings and perfect-information games do not apply. This paper introduces a principled way to conduct depth-limited solving in imperfect-information games by allowing the opponent to choose among a number of strategies for the remainder of the game at the depth limit. Each one of these strategies results in a different set of values for leaf nodes. This forces an agent to be robust to the different strategies an opponent may employ. We demonstrate the effectiveness of this approach by building a master-level heads-up no-limit Texas hold'em poker AI that defeats two prior top agents using only a 4-core CPU and 16 GB of memory. Developing such a powerful agent would have previously required a supercomputer.

##### Abstract (translated by Google)
不完美信息博弈中的一个根本挑战是国家没有明确的价值观。因此，在单一代理设置和完美信息游戏中使用的深度限制搜索算法不适用。本文介绍了一种在不完美信息博弈中进行有限深度求解的原则性方法，通过允许对手在深度限制下为游戏的其余部分选择多种策略。这些策略中的每一个都会为叶节点生成一组不同的值。这迫使代理对对手可能采用的不同策略具有强大的作用。我们通过构建一个主控级无限德州扑克AI，证明了这种方法的有效性，该AI仅使用4核CPU和16 GB内存来击败前两个顶级代理。开发这样一个强大的代理人以前需要一台超级计算机。

##### URL
[http://arxiv.org/abs/1805.08195](http://arxiv.org/abs/1805.08195)

##### PDF
[http://arxiv.org/pdf/1805.08195](http://arxiv.org/pdf/1805.08195)

