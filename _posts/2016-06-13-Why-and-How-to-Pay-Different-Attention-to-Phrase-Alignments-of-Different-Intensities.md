---
layout: post
title: "Why and How to Pay Different Attention to Phrase Alignments of Different Intensities"
date: 2016-06-13 06:41:21
categories: arXiv_CL
tags: arXiv_CL Attention Face Represenation_Learning Classification
author: Wenpeng Yin, Hinrich Schütze
mathjax: true
---

* content
{:toc}

##### Abstract
This work studies comparatively two typical sentence pair classification tasks: textual entailment (TE) and answer selection (AS), observing that phrase alignments of different intensities contribute differently in these tasks. We address the problems of identifying phrase alignments of flexible granularity and pooling alignments of different intensities for these tasks. Examples for flexible granularity are alignments between two single words, between a single word and a phrase and between a short phrase and a long phrase. By intensity we roughly mean the degree of match, it ranges from identity over surface-form co-occurrence, rephrasing and other semantic relatedness to unrelated words as in lots of parenthesis text. Prior work (i) has limitations in phrase generation and representation, or (ii) conducts alignment at word and phrase levels by handcrafted features or (iii) utilizes a single attention mechanism over alignment intensities without considering the characteristics of specific tasks, which limits the system's effectiveness across tasks. We propose an architecture based on Gated Recurrent Unit that supports (i) representation learning of phrases of arbitrary granularity and (ii) task-specific focusing of phrase alignments between two sentences by attention pooling. Experimental results on TE and AS match our observation and are state-of-the-art.

##### Abstract (translated by Google)
本研究比较两个典型的句对分类任务：文本包含（TE）和答案选择（AS），观察不同强度的短语对齐在这些任务中作出不同的贡献。我们解决了确定灵活粒度的词组对齐以及为这些任务汇集不同强度的问题。灵活粒度的例子是两个单个单词之间，单个单词与短语之间以及短语与长句之间的对齐。通过强度，我们粗略地指的是匹配的程度，其范围从表面形式共现，改写和其他语义相关性的身份到许多括号内的文字。先前的工作（i）在短语产生和表示方面有局限性，或者（ii）通过手工特征在单词和短语级别进行协调，或者（iii）在不考虑特定任务的特征的情况下，系统跨任务的有效性。我们提出了一种基于门控递归单元的体系结构，它支持（i）任意粒度短语的表示学习和（ii）通过注意池合并两个句子之间的短语对齐的任务专用聚焦。 TE和AS的实验结果符合我们的观察，并且是最先进的。

##### URL
[https://arxiv.org/abs/1604.06896](https://arxiv.org/abs/1604.06896)

##### PDF
[https://arxiv.org/pdf/1604.06896](https://arxiv.org/pdf/1604.06896)

