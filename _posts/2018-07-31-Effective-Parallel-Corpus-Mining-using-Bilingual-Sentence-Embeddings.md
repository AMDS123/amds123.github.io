---
layout: post
title: "Effective Parallel Corpus Mining using Bilingual Sentence Embeddings"
date: 2018-07-31 16:32:50
categories: arXiv_CL
tags: arXiv_CL Embedding NMT
author: Mandy Guo, Qinlan Shen, Yinfei Yang, Heming Ge, Daniel Cer, Gustavo Hernandez Abrego, Keith Stevens, Yun-Hsuan Sung, Brian Strope, Ray Kurzweil
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an effective approach for parallel corpus mining using bilingual sentence embeddings. Our embedding models are trained to produce similar representations exclusively for bilingual sentence pairs that are translations of each other. This is achieved using a novel training method that introduces hard negatives consisting of sentences that are not translations but that have some degree of semantic similarity. The quality of the resulting embeddings are evaluated on parallel corpus reconstruction and by assessing machine translation systems trained on gold vs.\ mined sentence pairs. We find that the sentence embeddings can be used to reconstruct the United Nations Parallel Corpus at the sentence level with a precision of 48.9\% for en-fr and 54.9\% for en-es. When adapted to document level matching, we achieve a parallel document matching accuracy that is comparable to the significantly more computationally intensive approach of [Jakob 2010]. Using reconstructed parallel data, we are able to train NMT models that perform nearly as well as models trained on the original data (within 1-2 BLEU).

##### Abstract (translated by Google)
本文提出了一种使用双语句嵌入的并行语料库挖掘的有效方法。我们的嵌入模型经过训练，专门为双语句对生成相似的表示，这些双语句对是彼此的翻译。这是通过一种新颖的训练方法来实现的，该方法引入了由不是翻译但具有某种程度的语义相似性的句子组成的硬否定。通过平行语料库重建和评估在黄金与\ n开句式对上训练的机器翻译系统来评估所得嵌入的质量。我们发现句子嵌入可用于在句子级别重建联合国平行语料库，en-fr的精度为48.9 \％，en-es的精度为54.9％。当适应文档级别匹配时，我们实现了并行文档匹配准确性，与[Jakob 2010]的计算密集型方法相当。使用重建的并行数据，我们能够训练NMT模型，其性能几乎与在原始数据上训练的模型（1-2 BLEU内）一样好。

##### URL
[http://arxiv.org/abs/1807.11906](http://arxiv.org/abs/1807.11906)

##### PDF
[http://arxiv.org/pdf/1807.11906](http://arxiv.org/pdf/1807.11906)

