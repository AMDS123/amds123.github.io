---
layout: post
title: "Predicting Target Language CCG Supertags Improves Neural Machine Translation"
date: 2017-07-18 12:07:45
categories: arXiv_CL
tags: arXiv_CL NMT
author: Maria Nadejde, Siva Reddy, Rico Sennrich, Tomasz Dwojak, Marcin Junczys-Dowmunt, Philipp Koehn, Alexandra Birch
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) models are able to partially learn syntactic information from sequential lexical information. Still, some complex syntactic phenomena such as prepositional phrase attachment are poorly modeled. This work aims to answer two questions: 1) Does explicitly modeling target language syntax help NMT? 2) Is tight integration of words and syntax better than multitask training? We introduce syntactic information in the form of CCG supertags in the decoder, by interleaving the target supertags with the word sequence. Our results on WMT data show that explicitly modeling target-syntax improves machine translation quality for German->English, a high-resource pair, and for Romanian->English, a low-resource pair and also several syntactic phenomena including prepositional phrase attachment. Furthermore, a tight coupling of words and syntax improves translation quality more than multitask training. By combining target-syntax with adding source-side dependency labels in the embedding layer, we obtain a total improvement of 0.9 BLEU for German->English and 1.2 BLEU for Romanian->English.

##### Abstract (translated by Google)
神经机器翻译（NMT）模型能够从连续的词汇信息中部分地学习句法信息。尽管如此，一些复杂的句法现象，如介词短语依恋模型也很差。这项工作旨在回答两个问题：1）是否明确建模目标语言的语法帮助NMT？ 2）单词和句法的紧密整合比多任务训练更好吗？我们在解码器中以CCG超标记的形式引入句法信息，通过交织目标字段和字序列。我们在WMT数据上的结果显示，明确地建模目标语法提高了德语 - >英语，高资源对和罗马尼亚语 - >英语的机器翻译质量，低资源对和几个句法现象，包括介词短语附加。此外，单词和句法的紧密结合比多任务训练更能提高翻译质量。通过在嵌入层中结合目标语法和添加源端依赖标签，我们获得了德语 - 英语0.9 BLEU和罗马尼亚 - 英语1.2 BLEU的总体改进。

##### URL
[https://arxiv.org/abs/1702.01147](https://arxiv.org/abs/1702.01147)

