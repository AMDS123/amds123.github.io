---
layout: post
title: "Effective Inference for Generative Neural Parsing"
date: 2017-07-27 18:01:18
categories: arXiv_CL
tags: arXiv_CL Inference
author: Mitchell Stern, Daniel Fried, Dan Klein
mathjax: true
---

* content
{:toc}

##### Abstract
Generative neural models have recently achieved state-of-the-art results for constituency parsing. However, without a feasible search procedure, their use has so far been limited to reranking the output of external parsers in which decoding is more tractable. We describe an alternative to the conventional action-level beam search used for discriminative neural models that enables us to decode directly in these generative models. We then show that by improving our basic candidate selection strategy and using a coarse pruning function, we can improve accuracy while exploring significantly less of the search space. Applied to the model of Choe and Charniak (2016), our inference procedure obtains 92.56 F1 on section 23 of the Penn Treebank, surpassing prior state-of-the-art results for single-model systems.

##### Abstract (translated by Google)
生成神经模型最近已经为选区分析实现了最先进的结果。然而，如果没有可行的搜索程序，它们的使用迄今为止仅限于重新排列解码更易于处理的外部解析器的输出。我们描述了用于区分性神经模型的常规动作级别波束搜索的替代方案，其使得我们能够在这些生成模型中直接解码。然后，我们表明，通过改进我们的基本候选人选择策略，并使用粗略的修剪功能，我们可以提高准确性，同时探索显着更少的搜索空间。根据Choe和Charniak（2016）的模型，我们的推理程序在Penn Treebank的第23部分获得了92.56的F1，超过了单一模型系统的先前的最新结果。

##### URL
[https://arxiv.org/abs/1707.08976](https://arxiv.org/abs/1707.08976)

##### PDF
[https://arxiv.org/pdf/1707.08976](https://arxiv.org/pdf/1707.08976)

