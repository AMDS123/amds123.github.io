---
layout: post
title: "Multi-Source Neural Machine Translation with Missing Data"
date: 2018-06-07 06:11:34
categories: arXiv_CL
tags: arXiv_CL NMT
author: Yuta Nishimura, Katsuhito Sudoh, Graham Neubig, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-source translation is an approach to exploit multiple inputs (e.g. in two different languages) to increase translation accuracy. In this paper, we examine approaches for multi-source neural machine translation (NMT) using an incomplete multilingual corpus in which some translations are missing. In practice, many multilingual corpora are not complete due to the difficulty to provide translations in all of the relevant languages (for example, in TED talks, most English talks only have subtitles for a small portion of the languages that TED supports). Existing studies on multi-source translation did not explicitly handle such situations. This study focuses on the use of incomplete multilingual corpora in multi-encoder NMT and mixture of NMT experts and examines a very simple implementation where missing source translations are replaced by a special symbol &lt;NULL&gt;. These methods allow us to use incomplete corpora both at training time and test time. In experiments with real incomplete multilingual corpora of TED Talks, the multi-source NMT with the &lt;NULL&gt; tokens achieved higher translation accuracies measured by BLEU than those by any one-to-one NMT systems.

##### Abstract (translated by Google)
多源翻译是一种利用多个输入（例如以两种不同语言）来提高翻译准确性的方法。在本文中，我们使用不完整的多语言语料库来研究多源神经机器翻译（NMT）的方法，其中一些翻译缺失。实际上，由于难以提供所有相关语言的翻译，许多多语种语料库并不完整（例如，在TED会谈中，大多数英语会话只有TED支持的一小部分语言的字幕）。关于多源翻译的现有研究没有明确处理这种情况。本研究集中于在多编码器NMT和NMT专家混合中使用不完整的多语种语料库，并检查了非常简单的实现，其中缺少源翻译被特殊符号＆lt; NULL＆gt;代替。这些方法允许我们在训练时间和测试时间使用不完整的语料库。在使用TED会话的真实不完全多语种语料库的实验中，具有＆lt; NULL＆gt;的多源NMT令牌比BLEU测量的任何一对一NMT系统的翻译准确度都要高。

##### URL
[http://arxiv.org/abs/1806.02525](http://arxiv.org/abs/1806.02525)

##### PDF
[http://arxiv.org/pdf/1806.02525](http://arxiv.org/pdf/1806.02525)

