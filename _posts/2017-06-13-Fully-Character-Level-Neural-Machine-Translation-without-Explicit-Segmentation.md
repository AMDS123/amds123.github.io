---
layout: post
title: "Fully Character-Level Neural Machine Translation without Explicit Segmentation"
date: 2017-06-13 03:32:34
categories: arXiv_CL
tags: arXiv_CL Segmentation CNN NMT
author: Jason Lee, Kyunghyun Cho, Thomas Hofmann
---

* content
{:toc}

##### Abstract
Most existing machine translation systems operate at the level of words, relying on explicit segmentation to extract tokens. We introduce a neural machine translation (NMT) model that maps a source character sequence to a target character sequence without any segmentation. We employ a character-level convolutional network with max-pooling at the encoder to reduce the length of source representation, allowing the model to be trained at a speed comparable to subword-level models while capturing local regularities. Our character-to-character model outperforms a recently proposed baseline with a subword-level encoder on WMT'15 DE-EN and CS-EN, and gives comparable performance on FI-EN and RU-EN. We then demonstrate that it is possible to share a single character-level encoder across multiple languages by training a model on a many-to-one translation task. In this multilingual setting, the character-level encoder significantly outperforms the subword-level encoder on all the language pairs. We observe that on CS-EN, FI-EN and RU-EN, the quality of the multilingual character-level translation even surpasses the models specifically trained on that language pair alone, both in terms of BLEU score and human judgment.

##### Abstract (translated by Google)
大多数现有的机器翻译系统都是在单词级别上进行操作的，依靠明确的分割来提取令牌。我们引入一个神经机器翻译（NMT）模型，将源字符序列映射到目标字符序列而不需要任何分割。我们在编码器上采用了一个字符级的卷积网络，以减少源表示的长度，使得模型能够以与子字级模型相当的速度进行训练，同时捕获局部规则。我们的字符到字符模型比WMT'15 DE-EN和CS-EN上的子字级编码器优于最近提出的基线，并且在FI-EN和RU-EN上具有可比较的性能。然后我们证明，通过在多对一的翻译任务上训练模型，可以跨多种语言共享单个字符级别的编码器。在这种多语言设置中，字符级编码器在所有语言对上的性能明显优于子字级编码器。我们注意到，在CS-EN，FI-EN和RU-EN中，多语言字符级翻译的质量甚至超过了单独在语言对上专门训练的模型，无论是BLEU得分还是人为判断。

##### URL
[https://arxiv.org/abs/1610.03017](https://arxiv.org/abs/1610.03017)

