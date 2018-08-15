---
layout: post
title: "Discrete Structural Planning for Neural Machine Translation"
date: 2018-08-14 05:13:23
categories: arXiv_CL
tags: arXiv_CL
author: Raphael Shu, Hideki Nakayama
mathjax: true
---

* content
{:toc}

##### Abstract
Structural planning is important for producing long sentences, which is a missing part in current language generation models. In this work, we add a planning phase in neural machine translation to control the coarse structure of output sentences. The model first generates some planner codes, then predicts real output words conditioned on them. The codes are learned to capture the coarse structure of the target sentence. In order to obtain the codes, we design an end-to-end neural network with a discretization bottleneck, which predicts the simplified part-of-speech tags of target sentences. Experiments show that the translation performance are generally improved by planning ahead. We also find that translations with different structures can be obtained by manipulating the planner codes.

##### Abstract (translated by Google)
结构规划对于产生长句很重要，这是当前语言生成模型中缺失的部分。在这项工作中，我们在神经机器翻译中添加了一个计划阶段来控制输出句子的粗略结构。该模型首先生成一些规划器代码，然后预测以它们为条件的实际输出字。学习代码以捕获目标句子的粗略结构。为了获得代码，我们设计了一个具有离散化瓶颈的端到端神经网络，它预测了目标句子的简化词性标签。实验表明，通过提前规划，通常可以提高翻译绩效。我们还发现通过操纵规划器代码可以获得具有不同结构的翻译。

##### URL
[http://arxiv.org/abs/1808.04525](http://arxiv.org/abs/1808.04525)

##### PDF
[http://arxiv.org/pdf/1808.04525](http://arxiv.org/pdf/1808.04525)

