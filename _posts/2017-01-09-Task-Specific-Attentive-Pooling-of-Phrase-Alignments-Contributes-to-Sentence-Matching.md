---
layout: post
title: "Task-Specific Attentive Pooling of Phrase Alignments Contributes to Sentence Matching"
date: 2017-01-09 12:03:11
categories: arXiv_SD
tags: arXiv_SD Attention Represenation_Learning Detection
author: Wenpeng Yin, Hinrich Schütze
mathjax: true
---

* content
{:toc}

##### Abstract
This work studies comparatively two typical sentence matching tasks: textual entailment (TE) and answer selection (AS), observing that weaker phrase alignments are more critical in TE, while stronger phrase alignments deserve more attention in AS. The key to reach this observation lies in phrase detection, phrase representation, phrase alignment, and more importantly how to connect those aligned phrases of different matching degrees with the final classifier. Prior work (i) has limitations in phrase generation and representation, or (ii) conducts alignment at word and phrase levels by handcrafted features or (iii) utilizes a single framework of alignment without considering the characteristics of specific tasks, which limits the framework's effectiveness across tasks. We propose an architecture based on Gated Recurrent Unit that supports (i) representation learning of phrases of arbitrary granularity and (ii) task-specific attentive pooling of phrase alignments between two sentences. Experimental results on TE and AS match our observation and show the effectiveness of our approach.

##### Abstract (translated by Google)
本研究比较了两个典型的句子匹配任务：文本蕴涵（TE）和答案选择（AS），认为在TE中较弱的短语对齐更为重要，而较强的短语对齐则更值得关注。实现这一观察的关键在于短语检测，短语表示，短语对齐，更重要的是如何将不同匹配度的对齐短语与最终分类器连接起来。之前的工作（i）在短语产生和表示方面有局限性，或者（ii）通过手工特征在单词和短语层面进行调整，或者（iii）利用单一调整框架而不考虑具体任务的特点，这限制了框架的有效性跨任务。我们提出了一个基于门控递归单元的架构，它支持（i）任意粒度短语的表示学习和（ii）两个句子之间短语对齐的任务特定注意池。 TE和AS的实验结果符合我们的观察结果，并显示了我们的方法的有效性。

##### URL
[https://arxiv.org/abs/1701.02149](https://arxiv.org/abs/1701.02149)

##### PDF
[https://arxiv.org/pdf/1701.02149](https://arxiv.org/pdf/1701.02149)

