---
layout: post
title: 'Paying Attention to Multi-Word Expressions in Neural Machine Translation'
date: 2017-10-17 14:27:36
categories: arXiv_CL
tags: arXiv_CL NMT
author: Matīss Rikters, Ondřej Bojar
---

* content
{:toc}

##### Abstract
Processing of multi-word expressions (MWEs) is a known problem for any natural language processing task. Even neural machine translation (NMT) struggles to overcome it. This paper presents results of experiments on investigating NMT attention allocation to the MWEs and improving automated translation of sentences that contain MWEs in English->Latvian and English->Czech NMT systems. Two improvement strategies were explored -(1) bilingual pairs of automatically extracted MWE candidates were added to the parallel corpus used to train the NMT system, and (2) full sentences containing the automatically extracted MWE candidates were added to the parallel corpus. Both approaches allowed to increase automated evaluation results. The best result - 0.99 BLEU point increase - has been reached with the first approach, while with the second approach minimal improvements achieved. We also provide open-source software and tools used for MWE extraction and alignment inspection.

##### Abstract (translated by Google)
对于任何自然语言处理任务来说，多词表达式（MWE）的处理是已知的问题。即使神经机器翻译（NMT）努力克服它。本文介绍了在英语 - >拉脱维亚语和英语 - >捷克语NMT系统中调查NMT对MWE注意分配的实验结果，并改进了包含MWE的句子的自动翻译。研究了两种改进策略：（1）将双语自动提取的MWE候选人添加到用于训练NMT系统的平行语料库中;（2）将包含自动提取的MWE候选者的完整句子添加到平行语料库中。两种方法都可以增加自动评估结果。最好的结果 -  0.99 BLEU点增加 - 已经达到了第一种方法，而第二种方法达到了最小的改善。我们还提供用于MWE提取和对齐检查的开源软件和工具。

##### URL
[https://arxiv.org/abs/1710.06313](https://arxiv.org/abs/1710.06313)

