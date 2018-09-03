---
layout: post
title: "Beyond Weight Tying: Learning Joint Input-Output Embeddings for Neural Machine Translation"
date: 2018-08-31 11:14:36
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Relation
author: Nikolaos Pappas, Lesly Miculicich Werlen, James Henderson
mathjax: true
---

* content
{:toc}

##### Abstract
Tying the weights of the target word embeddings with the target word classifiers of neural machine translation models leads to faster training and often to better translation quality. Given the success of this parameter sharing, we investigate other forms of sharing in between no sharing and hard equality of parameters. In particular, we propose a structure-aware output layer which captures the semantic structure of the output space of words within a joint input-output embedding. The model is a generalized form of weight tying which shares parameters but allows learning a more flexible relationship with input word embeddings and allows the effective capacity of the output layer to be controlled. In addition, the model shares weights across output classifiers and translation contexts which allows it to better leverage prior knowledge about them. Our evaluation on English-to-Finnish and English-to-German datasets shows the effectiveness of the method against strong encoder-decoder baselines trained with or without weight tying.

##### Abstract (translated by Google)
将目标词嵌入的权重与神经机器翻译模型的目标词分类器联系起来导致更快的训练并且通常提高翻译质量。鉴于此参数共享的成功，我们调查了无共享和参数硬性相等之间的其他共享形式。特别地，我们提出了一种结构感知输出层，它捕获联合输入 - 输出嵌入中字的输出空间的语义结构。该模型是权重绑定的一种通用形式，它共享参数但允许学习与输入字嵌入更灵活的关系，并允许控制输出层的有效容量。此外，该模型在输出分类器和翻译上下文之间共享权重，这使其能够更好地利用有关它们的先验知识。我们对英语到芬兰语和英语到德语数据集的评估显示了该方法对于使用或不使用权重绑定进行训练的强编码器 - 解码器基线的有效性。

##### URL
[http://arxiv.org/abs/1808.10681](http://arxiv.org/abs/1808.10681)

##### PDF
[http://arxiv.org/pdf/1808.10681](http://arxiv.org/pdf/1808.10681)

