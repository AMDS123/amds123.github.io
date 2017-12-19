---
layout: post
title: "Augmenting Phrase Table by Employing Lexicons for Pivot-based SMT"
date: 2015-12-01 08:10:49
categories: arXiv_CL
tags: arXiv_CL Sparse
author: Yiming Cui, Conghui Zhu, Xiaoning Zhu, Tiejun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Pivot language is employed as a way to solve the data sparseness problem in machine translation, especially when the data for a particular language pair does not exist. The combination of source-to-pivot and pivot-to-target translation models can induce a new translation model through the pivot language. However, the errors in two models may compound as noise, and still, the combined model may suffer from a serious phrase sparsity problem. In this paper, we directly employ the word lexical model in IBM models as an additional resource to augment pivot phrase table. In addition, we also propose a phrase table pruning method which takes into account both of the source and target phrasal coverage. Experimental result shows that our pruning method significantly outperforms the conventional one, which only considers source side phrasal coverage. Furthermore, by including the entries in the lexicon model, the phrase coverage increased, and we achieved improved results in Chinese-to-Japanese translation using English as pivot language.

##### Abstract (translated by Google)
枢轴语言被用作解决机器翻译中的数据稀疏问题的一种方式，特别是当特定语言对的数据不存在时。源到枢轴和枢转到目标翻译模型的组合可以通过枢轴语言引起新的翻译模型。然而，两个模型中的误差可能会混合为噪声，而组合模型可能会遭受严重的短语稀疏问题。在本文中，我们直接在IBM模型中使用词汇模型作为附加资源来扩充枢轴短语表。另外，我们还提出了一个短语表修剪方法，它考虑了源和目标短语的覆盖范围。实验结果表明，我们的修剪方法明显优于传统的修剪方法，仅考虑源语短语的覆盖范围。此外，通过在词典模型中包含条目，词组覆盖范围增加，并且使用英语作为枢轴语言在中日翻译方面取得了改进的结果。

##### URL
[https://arxiv.org/abs/1512.00170](https://arxiv.org/abs/1512.00170)

##### PDF
[https://arxiv.org/pdf/1512.00170](https://arxiv.org/pdf/1512.00170)

