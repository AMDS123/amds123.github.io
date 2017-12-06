---
layout: post
title: "An Empirical Study of Mini-Batch Creation Strategies for Neural Machine Translation"
date: 2017-06-19 02:38:01
categories: arXiv_CL
tags: arXiv_CL NMT
author: Makoto Morishita, Yusuke Oda, Graham Neubig, Koichiro Yoshino, Katsuhito Sudoh, Satoshi Nakamura
---

* content
{:toc}

##### Abstract
Training of neural machine translation (NMT) models usually uses mini-batches for efficiency purposes. During the mini-batched training process, it is necessary to pad shorter sentences in a mini-batch to be equal in length to the longest sentence therein for efficient computation. Previous work has noted that sorting the corpus based on the sentence length before making mini-batches reduces the amount of padding and increases the processing speed. However, despite the fact that mini-batch creation is an essential step in NMT training, widely used NMT toolkits implement disparate strategies for doing so, which have not been empirically validated or compared. This work investigates mini-batch creation strategies with experiments over two different datasets. Our results suggest that the choice of a mini-batch creation strategy has a large effect on NMT training and some length-based sorting strategies do not always work well compared with simple shuffling.

##### Abstract (translated by Google)
神经机器翻译（NMT）模型的训练通常使用小批量来提高效率。在小批量训练过程中，为了有效计算，需要在一个小批量中填充较短的句子长度与其中最长的句子相等。先前的工作已经注意到，在进行小批量之前基于句子长度对语料进行排序减少了填充量并提高了处理速度。然而，尽管小批量创建是NMT培训的一个重要步骤，但是广泛使用的NMT工具包实施了不同的策略，这些策略尚未经过实证验证或比较。本工作通过两个不同数据集的实验来调查小批量创建策略。我们的研究结果表明，小批量创建策略的选择对NMT培训有很大的影响，而且一些基于长度的分类策略与简单的洗牌相比并不总是奏效。

##### URL
[https://arxiv.org/abs/1706.05765](https://arxiv.org/abs/1706.05765)

