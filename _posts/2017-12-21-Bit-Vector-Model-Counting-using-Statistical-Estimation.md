---
layout: post
title: "Bit-Vector Model Counting using Statistical Estimation"
date: 2017-12-21 02:05:25
categories: arXiv_AI
tags: arXiv_AI Inference Quantitative
author: Seonmo Kim, Stephen McCamant
mathjax: true
---

* content
{:toc}

##### Abstract
Approximate model counting for bit-vector SMT formulas (generalizing \#SAT) has many applications such as probabilistic inference and quantitative information-flow security, but it is computationally difficult. Adding random parity constraints (XOR streamlining) and then checking satisfiability is an effective approximation technique, but it requires a prior hypothesis about the model count to produce useful results. We propose an approach inspired by statistical estimation to continually refine a probabilistic estimate of the model count for a formula, so that each XOR-streamlined query yields as much information as possible. We implement this approach, with an approximate probability model, as a wrapper around an off-the-shelf SMT solver or SAT solver. Experimental results show that the implementation is faster than the most similar previous approaches which used simpler refinement strategies. The technique also lets us model count formulas over floating-point constraints, which we demonstrate with an application to a vulnerability in differential privacy mechanisms.

##### Abstract (translated by Google)
位矢量SMT公式（通用\ #SAT）的近似模型计数有许多应用，如概率推理和定量信息流安全性，但计算困难。添加随机奇偶约束（异或优化），然后检查可满足性是一种有效的近似技术，但它需要关于模型计数的先验假设才能产生有用的结果。我们提出了一种受统计估计启发的方法，以不断改进对公式的模型计数的概率估计，以便每个异或 - 精简查询产生尽可能多的信息。我们用一个近似概率模型来实现这个方法，作为围绕现成的SMT求解器或SAT求解器的包装。实验结果表明，实施比以前使用较简单的细化策略的方法更为快速。该技术还可以让我们对浮点约束条件下的计数公式进行建模，我们通过应用程序来演示差分隐私机制中的漏洞。

##### URL
[http://arxiv.org/abs/1712.07770](http://arxiv.org/abs/1712.07770)

##### PDF
[http://arxiv.org/pdf/1712.07770](http://arxiv.org/pdf/1712.07770)

