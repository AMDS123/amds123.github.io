---
layout: post
title: "Modeling Target-Side Inflection in Neural Machine Translation"
date: 2017-09-05 09:29:10
categories: arXiv_CL
tags: arXiv_CL NMT
author: Aleš Tamchyna, Marion Weller-Di Marco, Alexander Fraser
---

* content
{:toc}

##### Abstract
NMT systems have problems with large vocabulary sizes. Byte-pair encoding (BPE) is a popular approach to solving this problem, but while BPE allows the system to generate any target-side word, it does not enable effective generalization over the rich vocabulary in morphologically rich languages with strong inflectional phenomena. We introduce a simple approach to overcome this problem by training a system to produce the lemma of a word and its morphologically rich POS tag, which is then followed by a deterministic generation step. We apply this strategy for English-Czech and English-German translation scenarios, obtaining improvements in both settings. We furthermore show that the improvement is not due to only adding explicit morphological information.

##### Abstract (translated by Google)
NMT系统有大量词汇量的问题。字节对编码（BPE）是解决这个问题的一种常用方法，但是BPE允许系统生成任何目标端词汇，但是它不能有效地推广形态丰富的语言中的丰富的词汇和强烈的屈折现象。我们引入一个简单的方法来克服这个问题，通过训练一个系统来产生一个词的词条及其形态丰富的POS标签，然后是一个确定性的生成步骤。我们将这一策略应用于英语 - 捷克语和英语 - 德语翻译场景，并在两个设置中获得改进。我们进一步表明，这种改进不是因为只添加了明确的形态信息。

##### URL
[https://arxiv.org/abs/1707.06012](https://arxiv.org/abs/1707.06012)

