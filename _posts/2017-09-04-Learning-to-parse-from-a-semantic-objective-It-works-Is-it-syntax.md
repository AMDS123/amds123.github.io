---
layout: post
title: "Learning to parse from a semantic objective: It works. Is it syntax?"
date: 2017-09-04 19:05:39
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Classification
author: Adina Williams, Andrew Drozdov, Samuel R. Bowman
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work on reinforcement learning and other gradient estimators for latent tree learning has made it possible to train neural networks that learn to both parse a sentence and use the resulting parse to interpret the sentence, all without exposure to ground-truth parse trees at training time. Surprisingly, these models often perform better at sentence understanding tasks than models that use parse trees from conventional parsers. This paper aims to investigate what these latent tree learning models learn. We replicate two such models in a shared codebase and find that (i) they do outperform baselines on sentence classification, but that (ii) their parsing strategies are not especially consistent across random restarts, (iii) the parses they produce tend to be shallower than PTB parses, and (iv) these do not resemble those of PTB or of any other recognizable semantic or syntactic grammar formalism.

##### Abstract (translated by Google)
最近在强化学习和其他潜在树学习的梯度估计器方面的工作使得训练神经网络成为可能，这些神经网络学习解析一个句子，并使用得到的解析来解释句子，所有这些都不需要在训练时间接触到地面真值分析树。令人惊讶的是，与使用传统解析器的解析树的模型相比，这些模型在语句理解任务上往往表现得更好。本文旨在调查这些潜在树木学习模型。我们在一个共享的代码库中复制两个这样的模型，发现：（i）它们在句子分类上的表现优于基线，但是（ii）它们的解析策略在随机重新开始时不是特别一致的;（iii）它们产生的分析倾向于更浅（四）这些不像PTB或任何其他可识别的语义或语法语法形式主义。

##### URL
[https://arxiv.org/abs/1709.01121](https://arxiv.org/abs/1709.01121)

##### PDF
[https://arxiv.org/pdf/1709.01121](https://arxiv.org/pdf/1709.01121)

