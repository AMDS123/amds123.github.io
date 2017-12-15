---
layout: post
title: "Neural Machine Translation with External Phrase Memory"
date: 2016-06-06 15:45:41
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Yaohua Tang, Fandong Meng, Zhengdong Lu, Hang Li, Philip L.H. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose phraseNet, a neural machine translator with a phrase memory which stores phrase pairs in symbolic form, mined from corpus or specified by human experts. For any given source sentence, phraseNet scans the phrase memory to determine the candidate phrase pairs and integrates tagging information in the representation of source sentence accordingly. The decoder utilizes a mixture of word-generating component and phrase-generating component, with a specifically designed strategy to generate a sequence of multiple words all at once. The phraseNet not only approaches one step towards incorporating external knowledge into neural machine translation, but also makes an effort to extend the word-by-word generation mechanism of recurrent neural network. Our empirical study on Chinese-to-English translation shows that, with carefully-chosen phrase table in memory, phraseNet yields 3.45 BLEU improvement over the generic neural machine translator.

##### Abstract (translated by Google)
在本文中，我们提出了一个带有短语记忆的神经机器翻译器phraseNet，它以符号形式存储短语对，从语料库挖掘或由专家指定。对于任何给定的源句子，phraseNet都会扫描短语记忆以确定候选短语对，并相应地将标记信息整合到源语句的表示中。解码器利用了词汇生成组件和短语生成组件的混合，并且具有专门设计的策略以一次生成多个词的序列。短语网不仅将外部知识融入神经机器翻译中，而且还努力延续循环神经网络的逐字生成机制。我们对中英文翻译的实证研究表明，在精心选择的短语表中，phraseNet与通用神经机器翻译相比，得到了3.45BLEU的改进。

##### URL
[https://arxiv.org/abs/1606.01792](https://arxiv.org/abs/1606.01792)

##### PDF
[https://arxiv.org/pdf/1606.01792](https://arxiv.org/pdf/1606.01792)

