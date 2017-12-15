---
layout: post
title: "Resolving Out-of-Vocabulary Words with Bilingual Embeddings in Machine Translation"
date: 2016-08-05 15:11:58
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Pranava Swaroop Madhyastha, Cristina España-Bonet
mathjax: true
---

* content
{:toc}

##### Abstract
Out-of-vocabulary words account for a large proportion of errors in machine translation systems, especially when the system is used on a different domain than the one where it was trained. In order to alleviate the problem, we propose to use a log-bilinear softmax-based model for vocabulary expansion, such that given an out-of-vocabulary source word, the model generates a probabilistic list of possible translations in the target language. Our model uses only word embeddings trained on significantly large unlabelled monolingual corpora and trains over a fairly small, word-to-word bilingual dictionary. We input this probabilistic list into a standard phrase-based statistical machine translation system and obtain consistent improvements in translation quality on the English-Spanish language pair. Especially, we get an improvement of 3.9 BLEU points when tested over an out-of-domain test set.

##### Abstract (translated by Google)
机器翻译系统中的错误词汇占据了很大的比例，特别是当系统在不同的领域被使用，而不是被训练的领域。为了缓解这个问题，我们建议使用基于对数线性的softmax模型进行词汇扩展，这样，如果给出一个词外词源，模型会生成一个可能的目标语言翻译的概率列表。我们的模型只使用在非常大的未标记的单语语料库上训练的单词嵌入，并在相当小的单词对双语词典上训练。我们将这个概率列表输入到一个标准的基于短语的统计机器翻译系统中，并且在英语 - 西班牙语对上获得翻译质量的持续改进。特别是，当通过域外测试集测试时，我们得到3.9 BLEU点的改进。

##### URL
[https://arxiv.org/abs/1608.01910](https://arxiv.org/abs/1608.01910)

##### PDF
[https://arxiv.org/pdf/1608.01910](https://arxiv.org/pdf/1608.01910)

