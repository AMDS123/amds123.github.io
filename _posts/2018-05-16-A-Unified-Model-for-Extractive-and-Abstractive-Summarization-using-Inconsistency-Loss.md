---
layout: post
title: "A Unified Model for Extractive and Abstractive Summarization using Inconsistency Loss"
date: 2018-05-16 12:17:09
categories: arXiv_CL
tags: arXiv_CL Attention Summarization
author: Wan-Ting Hsu, Chieh-Kai Lin, Ming-Ying Lee, Kerui Min, Jing Tang, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a unified model combining the strength of extractive and abstractive summarization. On the one hand, a simple extractive model can obtain sentence-level attention with high ROUGE scores but less readable. On the other hand, a more complicated abstractive model can obtain word-level dynamic attention to generate a more readable paragraph. In our model, sentence-level attention is used to modulate the word-level attention such that words in less attended sentences are less likely to be generated. Moreover, a novel inconsistency loss function is introduced to penalize the inconsistency between two levels of attentions. By end-to-end training our model with the inconsistency loss and original losses of extractive and abstractive models, we achieve state-of-the-art ROUGE scores while being the most informative and readable summarization on the CNN/Daily Mail dataset in a solid human evaluation.

##### Abstract (translated by Google)
我们提出了一个统一的模型，结合了抽取和抽象总结的强度。一方面，一个简单的抽取模型可以获得ROUGE分数较高但可读性较差的句子级关注。另一方面，一个更复杂的抽象模型可以获得单词级动态关注，以生成更具可读性的段落。在我们的模型中，句子层面的关注被用来调节单词层面的注意力，从而减少了参与句子少的词汇的产生。此外，还引入了新的不一致性损失函数来惩罚两个关注层之间的不一致性。通过端到端培训我们的模型，其中包括抽取模型和抽象模型的不一致性损失和原始损失，我们实现了最先进的ROUGE分数，同时作为CNN /每日邮报数据集中最具信息量和可读性的摘要，坚实的人性评估。

##### URL
[http://arxiv.org/abs/1805.06266](http://arxiv.org/abs/1805.06266)

##### PDF
[http://arxiv.org/pdf/1805.06266](http://arxiv.org/pdf/1805.06266)

