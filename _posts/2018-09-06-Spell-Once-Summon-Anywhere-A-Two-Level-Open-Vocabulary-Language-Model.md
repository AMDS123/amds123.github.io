---
layout: post
title: "Spell Once, Summon Anywhere: A Two-Level Open-Vocabulary Language Model"
date: 2018-09-06 18:26:20
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model
author: Sebastian J. Mielke, Jason Eisner
mathjax: true
---

* content
{:toc}

##### Abstract
We show how the spellings of known words can help us deal with unknown words in open-vocabulary NLP tasks. The method we propose can be used to extend any closed-vocabulary generative model, but in this paper we specifically consider the case of neural language modeling. Our Bayesian generative story combines a standard RNN language model (generating the word tokens in each sentence) with an RNN-based spelling model (generating the letters in each word type). These two RNNs respectively capture sentence structure and word structure, and are kept separate as in linguistics. By invoking the second RNN to generate spellings for novel words in context, we obtain an open-vocabulary language model. For known words, embeddings are naturally inferred by combining evidence from type spelling and token context. Comparing to baselines (including a novel strong baseline), we beat previous work and establish state-of-the-art results on multiple datasets.

##### Abstract (translated by Google)
我们展示了已知单词的拼写如何帮助我们处理开放词汇NLP任务中的未知单词。我们提出的方法可以用于扩展任何闭合词汇生成模型，但在本文中我们特别考虑了神经语言建模的情况。我们的贝叶斯生成故事结合了标准的RNN语言模型（在每个句子中生成单词标记）和基于RNN的拼写模型（生成每个单词类型中的字母）。这两个RNN分别捕获句子结构和单词结构，并且与语言学一样保持分离。通过调用第二个RNN为上下文中的新词生成拼写，我们获得了一个开放词汇语言模型。对于已知的单词，通过组合类型拼写和令牌上下文的证据自然地推断嵌入。与基线（包括新的强基线）相比，我们击败了以前的工作并在多个数据集上建立了最先进的结果。

##### URL
[http://arxiv.org/abs/1804.08205](http://arxiv.org/abs/1804.08205)

##### PDF
[http://arxiv.org/pdf/1804.08205](http://arxiv.org/pdf/1804.08205)

