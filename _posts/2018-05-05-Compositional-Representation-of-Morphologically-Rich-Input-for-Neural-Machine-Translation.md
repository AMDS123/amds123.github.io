---
layout: post
title: "Compositional Representation of Morphologically-Rich Input for Neural Machine Translation"
date: 2018-05-05 10:27:32
categories: arXiv_CL
tags: arXiv_CL Segmentation Embedding NMT
author: Duygu Ataman, Marcello Federico
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) models are typically trained with fixed-size input and output vocabularies, which creates an important bottleneck on their accuracy and generalization capability. As a solution, various studies proposed segmenting words into sub-word units and performing translation at the sub-lexical level. However, statistical word segmentation methods have recently shown to be prone to morphological errors, which can lead to inaccurate translations. In this paper, we propose to overcome this problem by replacing the source-language embedding layer of NMT with a bi-directional recurrent neural network that generates compositional representations of the input at any desired level of granularity. We test our approach in a low-resource setting with five languages from different morphological typologies, and under different composition assumptions. By training NMT to compose word representations from character n-grams, our approach consistently outperforms (from 1.71 to 2.48 BLEU points) NMT learning embeddings of statistically generated sub-word units.

##### Abstract (translated by Google)
神经机器翻译（NMT）模型通常使用固定尺寸的输入和输出词汇表进行训练，这对其准确性和泛化能力造成了重要瓶颈。作为一种解决方案，各种研究提出将单词分割成分词单位并在分词水平进行翻译。然而，统计分词方法最近表现出容易出现形态错误，这可能导致翻译不准确。在本文中，我们提出通过用双向循环神经网络代替NMT的源语言嵌入层来克服这个问题，该神经网络以任何期望的粒度水平生成输入的组成表示。我们在低资源环境中测试我们的方法，使用来自不同形态类型的五种语言，并在不同的组成假设下进行测试。通过训练NMT来组合字符n-gram的单词表示，我们的方法始终优于（从1.71到2.48 BLEU点）NMT学习统计生成的子单位单元的嵌入。

##### URL
[http://arxiv.org/abs/1805.02036](http://arxiv.org/abs/1805.02036)

##### PDF
[http://arxiv.org/pdf/1805.02036](http://arxiv.org/pdf/1805.02036)

