---
layout: post
title: 'Achieving Open Vocabulary Neural Machine Translation with Hybrid Word-Character Models'
date: 2017-12-06 09:36:23
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Minh-Thang Luong, Christopher D. Manning
---

* content
{:toc}

##### Abstract
Nearly all previous work on neural machine translation (NMT) has used quite restricted vocabularies, perhaps with a subsequent method to patch in unknown words. This paper presents a novel word-character solution to achieving open vocabulary NMT. We build hybrid systems that translate mostly at the word level and consult the character components for rare words. Our character-level recurrent neural networks compute source word representations and recover unknown target words when needed. The twofold advantage of such a hybrid approach is that it is much faster and easier to train than character-based ones; at the same time, it never produces unknown words as in the case of word-based models. On the WMT'15 English to Czech translation task, this hybrid approach offers an addition boost of +2.1-11.4 BLEU points over models that already handle unknown words. Our best system achieves a new state-of-the-art result with 20.7 BLEU score. We demonstrate that our character models can successfully learn to not only generate well-formed words for Czech, a highly-inflected language with a very complex vocabulary, but also build correct representations for English source words.

##### Abstract (translated by Google)
几乎所有以前关于神经机器翻译（NMT）的工作都使用了相当有限的词汇表，或许用后续的方法来修补未知的词汇。本文提出了一种新的词汇字符解决方案来实现开放词汇NMT。我们构建的混合系统主要是在单词级别进行翻译，并查阅罕见单词的字符组件。我们的字符级递归神经网络计算源词表示并在需要时恢复未知的目标词。这种混合方法的双重优势在于，比基于角色的训练更快更容易;与此同时，它也不会像基于单词的模型那样产生未知的单词。在WMT'15英语到捷克语的翻译任务中，这种混合方法比已经处理未知单词的模型提供了+ 2.1-11.4 BLEU点的附加提升。我们最好的系统以20.7 BLEU得分达到了一个新的最新的结果。我们证明，我们的人物模型可以成功地学习，不仅可以为捷克语生成形式良好的单词，这是一个非常复杂的词汇，高度弯曲的语言，而且还建立正确的英语源词表示。

##### URL
[https://arxiv.org/abs/1604.00788](https://arxiv.org/abs/1604.00788)

