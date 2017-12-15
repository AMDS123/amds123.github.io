---
layout: post
title: "Improving the Performance of Neural Machine Translation Involving Morphologically Rich Languages"
date: 2017-01-08 06:04:50
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention Embedding RNN Language_Model
author: Krupakar Hans, R S Milton
mathjax: true
---

* content
{:toc}

##### Abstract
The advent of the attention mechanism in neural machine translation models has improved the performance of machine translation systems by enabling selective lookup into the source sentence. In this paper, the efficiencies of translation using bidirectional encoder attention decoder models were studied with respect to translation involving morphologically rich languages. The English - Tamil language pair was selected for this analysis. First, the use of Word2Vec embedding for both the English and Tamil words improved the translation results by 0.73 BLEU points over the baseline RNNSearch model with 4.84 BLEU score. The use of morphological segmentation before word vectorization to split the morphologically rich Tamil words into their respective morphemes before the translation, caused a reduction in the target vocabulary size by a factor of 8. Also, this model (RNNMorph) improved the performance of neural machine translation by 7.05 BLEU points over the RNNSearch model used over the same corpus. Since the BLEU evaluation of the RNNMorph model might be unreliable due to an increase in the number of matching tokens per sentence, the performances of the translations were also compared by means of human evaluation metrics of adequacy, fluency and relative ranking. Further, the use of morphological segmentation also improved the efficacy of the attention mechanism.

##### Abstract (translated by Google)
神经机器翻译模型中关注机制的出现，通过对源句子进行选择性查找，提高了机器翻译系统的性能。本文研究了翻译涉及形态丰富的语言的翻译使用双向编码器注意解码器模型的效率。选择英语 - 泰米尔语对进行分析。首先，英语和泰米尔语词汇的Word2Vec嵌入的使用将基线RNNSearch模型的翻译结果提高了0.73 BLEU点，得分为4.84 BLEU。在词矢量化之前使用形态分割在翻译之前将形态丰富的泰米尔语单词拆分成它们各自的词素导致目标词汇大小减少了8倍。此外，该模型（RNNMorph）改善了神经机器由7.05 BLEU翻译指向在相同语料库上使用的RNNSearch模型。由于BLEU对RNNMorph模型的评估可能是不可靠的，因为每个句子的匹配令牌数量增加，翻译的表现也通过充分性，流畅性和相对排名的人类评估指标进行比较。此外，形态分割的使用也改善了注意力机制的功效。

##### URL
[https://arxiv.org/abs/1612.02482](https://arxiv.org/abs/1612.02482)

##### PDF
[https://arxiv.org/pdf/1612.02482](https://arxiv.org/pdf/1612.02482)

