---
layout: post
title: "KNPTC: Knowledge and Neural Machine Translation Powered Chinese Pinyin Typo Correction"
date: 2018-05-02 11:33:45
categories: arXiv_AI
tags: arXiv_AI Knowledge NMT
author: Hengyi Cai, Xingguang Ji, Yonghao Song, Yan Jin, Yang Zhang, Mairgup Mansur, Xiaofang Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Chinese pinyin input methods are very important for Chinese language processing. Actually, users may make typos inevitably when they input pinyin. Moreover, pinyin typo correction has become an increasingly important task with the popularity of smartphones and the mobile Internet. How to exploit the knowledge of users typing behaviors and support the typo correction for acronym pinyin remains a challenging problem. To tackle these challenges, we propose KNPTC, a novel approach based on neural machine translation (NMT). In contrast to previous work, KNPTC is able to integrate explicit knowledge into NMT for pinyin typo correction, and is able to learn to correct a variety of typos without the guidance of manually selected constraints or languagespecific features. In this approach, we first obtain the transition probabilities between adjacent letters based on large-scale real-life datasets. Then, we construct the "ground-truth" alignments of training sentence pairs by utilizing these probabilities. Furthermore, these alignments are integrated into NMT to capture sensible pinyin typo correction patterns. KNPTC is applied to correct typos in real-life datasets, which achieves 32.77% increment on average in accuracy rate of typo correction compared against the state-of-the-art system.

##### Abstract (translated by Google)
汉语拼音输入法对于中文处理非常重要。事实上，用户在输入拼音时可能会不可避免地发生拼写错误。此外，随着智能手机和移动互联网的普及，拼音错误校正已成为越来越重要的任务。如何利用用户输入行为的知识并支持首字母缩写拼音的拼写错误修正仍然是一个具有挑战性的问题。为了解决这些挑战，我们提出KNPTC，一种基于神经机器翻译（NMT）的新方法。与以前的工作不同，KNPTC能够将显式知识整合到NMT中进行拼音错字校正，并且能够学习纠正各种错别字，而无需人工选择的约束或语言特定功能的指导。在这种方法中，我们首先根据大规模实际数据集获取相邻字母之间的转换概率。然后，利用这些概率构造训练句对的“地面真值”对齐。此外，这些对齐被整合到NMT中以捕捉明智的拼音错字校正模式。 KNPTC用于纠正实际数据集中的拼写错误，与最先进的系统相比，错字校正的准确率平均提高32.77％。

##### URL
[https://arxiv.org/abs/1805.00741](https://arxiv.org/abs/1805.00741)

##### PDF
[https://arxiv.org/pdf/1805.00741](https://arxiv.org/pdf/1805.00741)

