---
layout: post
title: "Context-Dependent Word Representation for Neural Machine Translation"
date: 2016-07-03 02:18:16
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Heeyoul Choi, Kyunghyun Cho, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We first observe a potential weakness of continuous vector representations of symbols in neural machine translation. That is, the continuous vector representation, or a word embedding vector, of a symbol encodes multiple dimensions of similarity, equivalent to encoding more than one meaning of the word. This has the consequence that the encoder and decoder recurrent networks in neural machine translation need to spend substantial amount of their capacity in disambiguating source and target words based on the context which is defined by a source sentence. Based on this observation, in this paper we propose to contextualize the word embedding vectors using a nonlinear bag-of-words representation of the source sentence. Additionally, we propose to represent special tokens (such as numbers, proper nouns and acronyms) with typed symbols to facilitate translating those words that are not well-suited to be translated via continuous vectors. The experiments on En-Fr and En-De reveal that the proposed approaches of contextualization and symbolization improves the translation quality of neural machine translation systems significantly.

##### Abstract (translated by Google)
我们首先观察神经机器翻译中符号的连续向量表示的潜在弱点。也就是说，符号的连续矢量表示或单词嵌入矢量对相似度的多个维度进行编码，等同于编码该单词的多于一个含义。其结果是，神经机器翻译中的编码器和解码器循环网络需要花费大量的能力来基于由源句子定义的上下文来消除源和目标词的歧义。基于这个观察，在本文中，我们提出使用源句子的非线性bag-of-words表示语境化词语嵌入向量。此外，我们建议使用键入的符号来表示特殊的令牌（如数字，专有名词和首字母缩略词），以便于翻译那些不适合通过连续向量进行翻译的单词。 En-Fr和En-De上的实验表明，所提出的语境化和符号化方法显着提高了神经机器翻译系统的翻译质量。

##### URL
[https://arxiv.org/abs/1607.00578](https://arxiv.org/abs/1607.00578)

##### PDF
[https://arxiv.org/pdf/1607.00578](https://arxiv.org/pdf/1607.00578)

