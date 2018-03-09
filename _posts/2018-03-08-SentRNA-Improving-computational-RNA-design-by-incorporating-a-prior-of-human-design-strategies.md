---
layout: post
title: "SentRNA: Improving computational RNA design by incorporating a prior of human design strategies"
date: 2018-03-08 15:12:16
categories: arXiv_AI
tags: arXiv_AI
author: Jade Shi (EteRNA players), Rhiju Das, Vijay S. Pande
mathjax: true
---

* content
{:toc}

##### Abstract
Designing RNA sequences that fold into specific structures and perform desired biological functions is an emerging field in bioengineering with broad applications from intracellular chemical catalysis to cancer therapy via selective gene silencing. Effective RNA design requires first solving the inverse folding problem: given a target structure, propose a sequence that folds into that structure. Although significant progress has been made in developing computational algorithms for this purpose, current approaches are ineffective at designing sequences for complex targets, limiting their utility in real-world applications. However, an alternative that has shown significantly higher performance are human players of the online RNA design game EteRNA. Through many rounds of gameplay, these players have developed a collective library of "human" rules and strategies for RNA design that have proven to be more effective than current computational approaches, especially for complex targets. Here, we present an RNA design agent, SentRNA, which consists of a fully-connected neural network trained using the $eternasolves$ dataset, a set of $1.8 x 10^4$ player-submitted sequences across 724 unique targets. The agent first predicts an initial sequence for a target using the trained network, and then refines that solution if necessary using a short adaptive walk utilizing a canon of standard design moves. Through this approach, we observe SentRNA can learn and apply human-like design strategies to solve several complex targets previously unsolvable by any computational approach. We thus demonstrate that incorporating a prior of human design strategies into a computational agent can significantly boost its performance, and suggests a new paradigm for machine-based RNA design.

##### Abstract (translated by Google)
设计折叠成特定结构并执行期望的生物学功能的RNA序列是生物工程领域的新兴领域，具有从细胞内化学催化到通过选择性基因沉默的癌症治疗的广泛应用。有效的RNA设计需要首先解决逆折叠问题：给定一个目标结构，提出一个折叠到该结构中的序列。尽管为此目的开发计算算法取得了重大进展，但目前的方法在为复杂目标设计序列方面效果不佳，限制了其在实际应用中的实用性。然而，性能显着提高的替代品是在线RNA设计游戏EteRNA的人类玩家。通过多轮游戏玩法，这些玩家已经开发出了RNA设计的“人”规则和策略的集合库，该设计已被证明比现有的计算方法更有效，特别是对于复杂的目标。在这里，我们提供了一个RNA设计代理SentRNA，它包含一个完全连接的神经网络，它使用$ eternasolves $数据集进行训练，一组$ 8 x 10 ^ 4 $玩家提交的724个独特目标序列。智能体首先使用训练好的网络预测目标的初始序列，然后根据需要通过使用标准设计移动的快速自适应步行来优化该解决方案。通过这种方法，我们观察到SentRNA可以学习并应用人类设计策略来解决以前无法通过任何计算方法解决的复杂目标。因此，我们证明将先前的人类设计策略纳入计算代理可显着提升其性能，并为基于机器的RNA设计提供新的范例。

##### URL
[http://arxiv.org/abs/1803.03146](http://arxiv.org/abs/1803.03146)

##### PDF
[http://arxiv.org/pdf/1803.03146](http://arxiv.org/pdf/1803.03146)

