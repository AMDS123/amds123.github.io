---
layout: post
title: "Estimating the Probability of Meeting a Deadline in Hierarchical Plans"
date: 2017-12-24 19:47:45
categories: arXiv_AI
tags: arXiv_AI
author: Liat Cohen, Solomon Eyal Shimony, Gera Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
Given a hierarchical plan (or schedule) with uncertain task times, we propose a deterministic polynomial (time and memory) algorithm for estimating the probability that its meets a deadline, or, alternately, that its {\em makespan} is less than a given duration. Approximation is needed as it is known that this problem is NP-hard even for sequential plans (just, a sum of random variables). In addition, we show two new complexity results: (1) Counting the number of events that do not cross deadline is \#P-hard; (2)~Computing the expected makespan of a hierarchical plan is NP-hard. For the proposed approximation algorithm, we establish formal approximation bounds and show that the time and memory complexities grow polynomially with the required accuracy, the number of nodes in the plan, and with the size of the support of the random variables that represent the durations of the primitive tasks. We examine these approximation bounds empirically and demonstrate, using task networks taken from the literature, how our scheme outperforms sampling techniques and exact computation in terms of accuracy and run-time. As the empirical data shows much better error bounds than guaranteed, we also suggest a method for tightening the bounds in some cases.

##### Abstract (translated by Google)
给定一个具有不确定任务时间的等级计划（或时间表），我们提出一个确定性多项式（时间和记忆）算法来估计其符合最终期限的概率，或者，或者，它的{\ em makespan}小于给定的持续时间。因为已知这个问题即使对于顺序计划（仅仅是随机变量的总和）是NP难的，也需要近似值。另外，我们展示了两个新的复杂性结果：（1）计算不跨越期限的事件数量是\＃P-hard; （2）计算分层计划的预期完工时间是NP难的。对于所提出的近似算法，我们建立了形式化的近似界，并且表明时间和记忆的复杂度随着所需的精度，计划中节点的数量以及随机变量的支持的大小以多项式增长原始任务。我们用经验的方法来检验这些近似范围，并用文献中的任务网络来证明我们的方案在精度和运行时间上如何优于采样技术和精确计算。由于经验数据显示出比保证更好的误差界限，我们也提出了一些在某些情况下收紧界限的方法。

##### URL
[http://arxiv.org/abs/1503.01327](http://arxiv.org/abs/1503.01327)

##### PDF
[http://arxiv.org/pdf/1503.01327](http://arxiv.org/pdf/1503.01327)

