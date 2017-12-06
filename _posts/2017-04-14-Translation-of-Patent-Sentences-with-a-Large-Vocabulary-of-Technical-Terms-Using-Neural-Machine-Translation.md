---
layout: post
title: 'Translation of Patent Sentences with a Large Vocabulary of Technical Terms Using Neural Machine Translation'
date: 2017-04-14 19:36:54
categories: arXiv_CL
tags: arXiv_CL NMT
author: Zi Long, Takehito Utsuro, Tomoharu Mitsuhashi, Mikio Yamamoto
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT), a new approach to machine translation, has achieved promising results comparable to those of traditional approaches such as statistical machine translation (SMT). Despite its recent success, NMT cannot handle a larger vocabulary because training complexity and decoding complexity proportionally increase with the number of target words. This problem becomes even more serious when translating patent documents, which contain many technical terms that are observed infrequently. In NMTs, words that are out of vocabulary are represented by a single unknown token. In this paper, we propose a method that enables NMT to translate patent sentences comprising a large vocabulary of technical terms. We train an NMT system on bilingual data wherein technical terms are replaced with technical term tokens; this allows it to translate most of the source sentences except technical terms. Further, we use it as a decoder to translate source sentences with technical term tokens and replace the tokens with technical term translations using SMT. We also use it to rerank the 1,000-best SMT translations on the basis of the average of the SMT score and that of the NMT rescoring of the translated sentences with technical term tokens. Our experiments on Japanese-Chinese patent sentences show that the proposed NMT system achieves a substantial improvement of up to 3.1 BLEU points and 2.3 RIBES points over traditional SMT systems and an improvement of approximately 0.6 BLEU points and 0.8 RIBES points over an equivalent NMT system without our proposed technique.

##### Abstract (translated by Google)
神经机器翻译（NMT）是一种新的机器翻译方法，与统计机器翻译（SMT）等传统方法相比，取得了可喜的成果。尽管最近的成功，NMT不能处理更大的词汇量，因为训练复杂度和解码复杂度随着目标词的数量成比例地增加。在翻译专利文件时，这个问题变得更加严重，这些专利文件包含很多很少被观察到的技术术语。在NMT中，超出词汇的单词由单个未知标记表示。在本文中，我们提出一种方法，使NMT能够翻译包含大量专业词汇的专利句子。我们训练NMT系统的双语数据，其中技术术语替换为技术术语标记;这使得它可以翻译除技术术语外的大部分源句子。此外，我们将其用作解码器，将源句子与技术术语标记进行翻译，并使用SMT替换使用技术术语翻译的标记。我们还用它来根据SMT得分的平均值和NMT对技术术语标记的翻译句子的平均值重新排序1000个最佳的SMT翻译。我们对日中专利句子的实验表明，与传统的SMT系统相比，所提出的NMT系统实现了高达3.1BLEU点和2.3RIBES点的实质性改进，与没有等效NMT系统相比，提高了约0.6BLEU点和0.8RIBES点我们提出的技术。

##### URL
[https://arxiv.org/abs/1704.04521](https://arxiv.org/abs/1704.04521)

