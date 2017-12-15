---
layout: post
title: "Reporting Score Distributions Makes a Difference: Performance Study of LSTM-networks for Sequence Tagging"
date: 2017-07-31 14:25:24
categories: arXiv_CL
tags: arXiv_CL OCR RNN
author: Nils Reimers, Iryna Gurevych
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we show that reporting a single performance score is insufficient to compare non-deterministic approaches. We demonstrate for common sequence tagging tasks that the seed value for the random number generator can result in statistically significant (p < 10^-4) differences for state-of-the-art systems. For two recent systems for NER, we observe an absolute difference of one percentage point F1-score depending on the selected seed value, making these systems perceived either as state-of-the-art or mediocre. Instead of publishing and reporting single performance scores, we propose to compare score distributions based on multiple executions. Based on the evaluation of 50.000 LSTM-networks for five sequence tagging tasks, we present network architectures that produce both superior performance as well as are more stable with respect to the remaining hyperparameters.

##### Abstract (translated by Google)
在本文中，我们表明报告一个单一的绩效评分不足以比较非确定性方法。我们证明了对于常见的序列标记任务，随机数发生器的种子值可以导致最先进的系统具有统计显着性（p <10 ^ -4）差异。对于NER最近的两个系统，我们观察到一个百分点的F1分数的绝对差异取决于所选的种子值，使得这些系统被认为是最先进的或平庸的。我们建议比较基于多次执行的分数分布，而不是发布和报告单一的绩效分数。基于对五个序列标记任务的50.000个LSTM网络的评估，我们提出的网络体系结构既具有优异的性能，又相对于其余的超参数具有更高的稳定性。

##### URL
[https://arxiv.org/abs/1707.09861](https://arxiv.org/abs/1707.09861)

##### PDF
[https://arxiv.org/pdf/1707.09861](https://arxiv.org/pdf/1707.09861)

