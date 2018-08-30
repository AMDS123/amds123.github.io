---
layout: post
title: "Revisiting Character-Based Neural Machine Translation with Capacity and Compression"
date: 2018-08-29 17:46:50
categories: arXiv_CL
tags: arXiv_CL NMT
author: Colin Cherry, George Foster, Ankur Bapna, Orhan Firat, Wolfgang Macherey
mathjax: true
---

* content
{:toc}

##### Abstract
Translating characters instead of words or word-fragments has the potential to simplify the processing pipeline for neural machine translation (NMT), and improve results by eliminating hyper-parameters and manual feature engineering. However, it results in longer sequences in which each symbol contains less information, creating both modeling and computational challenges. In this paper, we show that the modeling problem can be solved by standard sequence-to-sequence architectures of sufficient depth, and that deep models operating at the character level outperform identical models operating over word fragments. This result implies that alternative architectures for handling character input are better viewed as methods for reducing computation time than as improved ways of modeling longer sequences. From this perspective, we evaluate several techniques for character-level NMT, verify that they do not match the performance of our deep character baseline model, and evaluate the performance versus computation time tradeoffs they offer. Within this framework, we also perform the first evaluation for NMT of conditional computation over time, in which the model learns which timesteps can be skipped, rather than having them be dictated by a fixed schedule specified before training begins.

##### Abstract (translated by Google)
翻译字符而不是单词或单词片段有可能简化神经机器翻译（NMT）的处理流程，并通过消除超参数和手动特征工程来改善结果。然而，它导致更长的序列，其中每个符号包含更少的信息，从而产生建模和计算挑战。在本文中，我们表明建模问题可以通过足够深度的标准序列到序列架构来解决，并且在字符级别操作的深度模型优于在字段上操作的相同模型。该结果意味着用于处理字符输入的替代架构被更好地视为用于减少计算时间的方法，而不是用于对更长序列建模的改进方式。从这个角度来看，我们评估了几种字符级NMT技术，验证它们与深度字符基线模型的性能不匹配，并评估它们提供的性能与计算时间之间的权衡。在此框架内，我们还对条件计算的NMT进行了第一次评估，其中模型学习可以跳过哪些时间步，而不是由训练开始前指定的固定时间表决定。

##### URL
[http://arxiv.org/abs/1808.09943](http://arxiv.org/abs/1808.09943)

##### PDF
[http://arxiv.org/pdf/1808.09943](http://arxiv.org/pdf/1808.09943)

