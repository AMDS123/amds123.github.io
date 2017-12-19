---
layout: post
title: "Structured Prediction of Sequences and Trees using Infinite Contexts"
date: 2015-03-09 10:35:10
categories: arXiv_SD
tags: arXiv_SD Prediction
author: Ehsan Shareghi, Gholamreza Haffari, Trevor Cohn, Ann Nicholson
mathjax: true
---

* content
{:toc}

##### Abstract
Linguistic structures exhibit a rich array of global phenomena, however commonly used Markov models are unable to adequately describe these phenomena due to their strong locality assumptions. We propose a novel hierarchical model for structured prediction over sequences and trees which exploits global context by conditioning each generation decision on an unbounded context of prior decisions. This builds on the success of Markov models but without imposing a fixed bound in order to better represent global phenomena. To facilitate learning of this large and unbounded model, we use a hierarchical Pitman-Yor process prior which provides a recursive form of smoothing. We propose prediction algorithms based on A* and Markov Chain Monte Carlo sampling. Empirical results demonstrate the potential of our model compared to baseline finite-context Markov models on part-of-speech tagging and syntactic parsing.

##### Abstract (translated by Google)
语言结构呈现出丰富的全球现象，但是由于其强烈的局部性假设，常用的马尔可夫模型无法充分描述这些现象。我们提出了一种新的层次模型，用于序列和树的结构化预测，它利用全局上下文来调节每一代决策的前一个决策的无限上下文。这是建立在马尔可夫模型的成功基础之上的，而不是为了更好地代表全球现象而强加固定的界限。为了便于学习这个庞大而无限的模型，我们使用了一个层次的Pitman-Yor过程，它提供了一个递归形式的平滑。我们提出了基于A *和马尔科夫链蒙特卡罗采样的预测算法。实证结果表明，我们的模型相比基线有限上下文马尔可夫模型在词性标注和句法分析上的潜力。

##### URL
[https://arxiv.org/abs/1503.02417](https://arxiv.org/abs/1503.02417)

##### PDF
[https://arxiv.org/pdf/1503.02417](https://arxiv.org/pdf/1503.02417)

