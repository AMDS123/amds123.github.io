---
layout: post
title: "Finding Better Subword Segmentation for Neural Machine Translation"
date: 2018-07-25 14:43:46
categories: arXiv_AI
tags: arXiv_AI Segmentation NMT
author: Yingting Wu, Hai Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
For different language pairs, word-level neural machine translation (NMT) models with a fixed-size vocabulary suffer from the same problem of representing out-of-vocabulary (OOV) words. The common practice usually replaces all these rare or unknown words with a &lt;UNK&gt; token, which limits the translation performance to some extent. Most of recent work handled such a problem by splitting words into characters or other specially extracted subword units to enable open-vocabulary translation. Byte pair encoding (BPE) is one of the successful attempts that has been shown extremely competitive by providing effective subword segmentation for NMT systems. In this paper, we extend the BPE style segmentation to a general unsupervised framework with three statistical measures: frequency (FRQ), accessor variety (AV) and description length gain (DLG). We test our approach on two translation tasks: German to English and Chinese to English. The experimental results show that AV and DLG enhanced systems outperform the FRQ baseline in the frequency weighted schemes at different significant levels.

##### Abstract (translated by Google)
对于不同的语言对，具有固定大小词汇的词级神经机器翻译（NMT）模型遭受表示词汇表外（OOV）词的相同问题。通常的做法通常用＆lt; UNK＆gt;取代所有这些罕见或未知的单词。令牌，它在一定程度上限制了翻译性能。大多数最近的工作通过将单词分成字符或其他专门提取的子单词单元来处理这样的问题，以实现开放式词汇翻译。字节对编码（BPE）是通过为NMT系统提供有效的子字段分割而显示出极具竞争力的成功尝试之一。在本文中，我们将BPE样式分段扩展到一般无监督框架，其中包含三个统计度量：频率（FRQ），访问者种类（AV）和描述长度增益（DLG）。我们在两个翻译任务上测试我们的方法：德语到英语和中文到英语。实验结果表明，AV和DLG增强系统在不同显着水平的频率加权方案中优于FRQ基线。

##### URL
[http://arxiv.org/abs/1807.09639](http://arxiv.org/abs/1807.09639)

##### PDF
[http://arxiv.org/pdf/1807.09639](http://arxiv.org/pdf/1807.09639)

