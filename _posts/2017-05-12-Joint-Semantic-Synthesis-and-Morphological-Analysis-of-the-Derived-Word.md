---
layout: post
title: "Joint Semantic Synthesis and Morphological Analysis of the Derived Word"
date: 2017-05-12 07:14:55
categories: arXiv_SD
tags: arXiv_SD Segmentation RNN
author: Ryan Cotterell, Hinrich Schütze
mathjax: true
---

* content
{:toc}

##### Abstract
Much like sentences are composed of words, words themselves are composed of smaller units. For example, the English word questionably can be analyzed as question+able+ly. However, this structural decomposition of the word does not directly give us a semantic representation of the word's meaning. Since morphology obeys the principle of compositionality, the semantics of the word can be systematically derived from the meaning of its parts. In this work, we propose a novel probabilistic model of word formation that captures both the analysis of a word w into its constituents segments and the synthesis of the meaning of w from the meanings of those segments. Our model jointly learns to segment words into morphemes and compose distributional semantic vectors of those morphemes. We experiment with the model on English CELEX data and German DerivBase (Zeller et al., 2013) data. We show that jointly modeling semantics increases both segmentation accuracy and morpheme F1 by between 3% and 5%. Additionally, we investigate different models of vector composition, showing that recurrent neural networks yield an improvement over simple additive models. Finally, we study the degree to which the representations correspond to a linguist's notion of morphological productivity.

##### Abstract (translated by Google)
就像句子由单词组成，单词本身是由较小的单位组成的。例如，可疑的英语单词可以分析为问题+能+ +。然而，这个单词的结构分解并不直接给我们一个单词意义的语义表示。由于形态遵循组合性原则，词的语义可以从其部分的含义系统地得出。在这项工作中，我们提出了一个新的概率模型的单词形成，它包含了一个单词w到它的组成部分的分析和从这些部分的含义w的意义的综合。我们的模型共同学习将单词分割成语素，并构成这些语素的分布语义向量。我们用英语CELEX数据和德国DerivBase（Zeller et al。，2013）数据进行实验。我们表明，联合建模语义增加了3％和5％的分词准确性和语素F1。另外，我们研究了不同的向量组成模型，显示递归神经网络比简单的可加模型产生了改进。最后，我们研究表征符合语言学家形态生产力概念的程度。

##### URL
[https://arxiv.org/abs/1701.00946](https://arxiv.org/abs/1701.00946)

##### PDF
[https://arxiv.org/pdf/1701.00946](https://arxiv.org/pdf/1701.00946)

