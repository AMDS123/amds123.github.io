---
layout: post
title: "Segmentation-free compositional $n$-gram embedding"
date: 2018-09-04 12:32:54
categories: arXiv_CL
tags: arXiv_CL Segmentation Embedding
author: Geewook Kim, Kazuki Fukui, Hidetoshi Shimodaira
mathjax: true
---

* content
{:toc}

##### Abstract
Applying conventional word embedding models to unsegmented languages, where word boundary is not clear, requires word segmentation as preprocessing. However, word segmentation is difficult and expensive to conduct without errors. Segmentation error degrades the quality of word embeddings, leading to performance degradation in downstream applications. In this paper, we propose a simple segmentation-free method to obtain unsupervised vector representations for words, phrases and sentences from an unsegmented raw corpus. Our model is based on subword information skip-gram model, but embedding targets and contexts are character $n$-grams instead of segmented words. We consider all possible character $n$-grams in a corpus as targets, and every target is modeled as the sum of its compositional sub-$n$-grams. Our method completely ignores word boundaries in a corpus and is not word-segmentation dependent. This approach may sound reckless, but it was found to work well through experiments on real-world datasets and benchmarks.

##### Abstract (translated by Google)
将传统的单词嵌入模型应用于未被明确的单边界的未分段语言，需要将分词作为预处理。然而，在没有错误的情况下进行分词是困难且昂贵的。分段错误会降低字嵌入的质量，从而导致下游应用程序的性能下降。在本文中，我们提出了一种简单的无分割方法，以获得来自未分段原始语料库的单词，短语和句子的无监督向量表示。我们的模型基于子字信息skip-gram模型，但嵌入目标和上下文是字符$ n $ -grams而不是分段字。我们将语料库中所有可能的字符$ n $ -grams视为目标，并且每个目标都被建模为其组成子$ $ n $ -grams的总和。我们的方法完全忽略语料库中的单词边界，而不依赖于单词分段。这种方法可能听起来鲁莽，但通过对真实数据集和基准测试的实验发现它可以很好地工作。

##### URL
[http://arxiv.org/abs/1809.00918](http://arxiv.org/abs/1809.00918)

##### PDF
[http://arxiv.org/pdf/1809.00918](http://arxiv.org/pdf/1809.00918)

