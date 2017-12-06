---
layout: post
title: 'Memory-enhanced Decoder for Neural Machine Translation'
date: 2017-12-06 09:36:23
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Mingxuan Wang, Zhengdong Lu, Hang Li, Qun Liu
---

* content
{:toc}

##### Abstract
We propose to enhance the RNN decoder in a neural machine translator (NMT) with external memory, as a natural but powerful extension to the state in the decoding RNN. This memory-enhanced RNN decoder is called \textsc{MemDec}. At each time during decoding, \textsc{MemDec} will read from this memory and write to this memory once, both with content-based addressing. Unlike the unbounded memory in previous work\cite{RNNsearch} to store the representation of source sentence, the memory in \textsc{MemDec} is a matrix with pre-determined size designed to better capture the information important for the decoding process at each time step. Our empirical study on Chinese-English translation shows that it can improve by $4.8$ BLEU upon Groundhog and $5.3$ BLEU upon on Moses, yielding the best performance achieved with the same training set.

##### Abstract (translated by Google)
我们建议在具有外部存储器的神经机器翻译器（NMT）中增强RNN解码器，作为在解码RNN中状态的自然但强大的扩展。这个内存增强的RNN解码器被称为\ textsc {MemDec}。在解码期间，\ textsc {MemDec}会从这个内存中读取数据并写入这个内存一次，都是基于内容的寻址。与以前工作中的无限存储器\ cite {RNNsearch}存储源语句的表示形式不同，\ textsc {MemDec}中的存储器是一个预定义大小的矩阵，旨在更好地捕获每次解码过程中重要的信息步。我们对中英文翻译的实证研究表明，在土拨鼠上可以提高4.8美元的BLEU，在摩西上可以提高5.3美元的BLEU，从而在同样的培训集上获得最好的表现。

##### URL
[https://arxiv.org/abs/1606.02003](https://arxiv.org/abs/1606.02003)

