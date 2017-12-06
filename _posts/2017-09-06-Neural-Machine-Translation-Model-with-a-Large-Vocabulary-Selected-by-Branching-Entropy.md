---
layout: post
title: 'Neural Machine Translation Model with a Large Vocabulary Selected by Branching Entropy'
date: 2017-09-06 04:06:07
categories: arXiv_CL
tags: arXiv_CL NMT
author: Zi Long, Ryuichiro Kimura, Takehito Utsuro, Tomoharu Mitsuhashi, Mikio Yamamoto
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT), a new approach to machine translation, has achieved promising results comparable to those of traditional approaches such as statistical machine translation (SMT). Despite its recent success, NMT cannot handle a larger vocabulary because the training complexity and decoding complexity proportionally increase with the number of target words. This problem becomes even more serious when translating patent documents, which contain many technical terms that are observed infrequently. In this paper, we propose to select phrases that contain out-of-vocabulary words using the statistical approach of branching entropy. This allows the proposed NMT system to be applied to a translation task of any language pair without any language-specific knowledge about technical term identification. The selected phrases are then replaced with tokens during training and post-translated by the phrase translation table of SMT. Evaluation on Japanese-to-Chinese, Chinese-to-Japanese, Japanese-to-English and English-to-Japanese patent sentence translation proved the effectiveness of phrases selected with branching entropy, where the proposed NMT model achieves a substantial improvement over a baseline NMT model without our proposed technique. Moreover, the number of translation errors of under-translation by the baseline NMT model without our proposed technique reduces to around half by the proposed NMT model.

##### Abstract (translated by Google)
神经机器翻译（NMT）是一种新的机器翻译方法，与统计机器翻译（SMT）等传统方法相比，取得了可喜的成果。尽管最近的成功，NMT不能处理更大的词汇量，因为训练复杂度和解码复杂度随着目标词的数量成比例地增加。在翻译专利文件时，这个问题变得更加严重，这些专利文件包含很多很少被观察到的技术术语。在本文中，我们建议使用分支熵的统计方法来选择包含词汇外词语的短语。这允许所提出的NMT系统被应用于任何语言对的翻译任务，而没有关于技术术语识别的任何语言特定的知识。所选择的短语在培训期间被标记替换，并由SMT的短语翻译表进行后翻译。对日语，汉语，日语，英语和英语日语专利句子翻译的评估证明了选择分支熵的短语的有效性，其中所提出的NMT模型在基线上实现了实质性改善NMT模型没有我们提出的技术。此外，没有我们提出的技术的基线NMT模型下翻译的平移误差数量减少到了所提出的NMT模型的一半左右。

##### URL
[https://arxiv.org/abs/1704.04520](https://arxiv.org/abs/1704.04520)

