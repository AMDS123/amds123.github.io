---
layout: post
title: "Memory-enhanced Decoder for Neural Machine Translation"
date: 2016-06-07 02:28:19
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Mingxuan Wang, Zhengdong Lu, Hang Li, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to enhance the RNN decoder in a neural machine translator (NMT) with external memory, as a natural but powerful extension to the state in the decoding RNN. This memory-enhanced RNN decoder is called \textsc{MemDec}. At each time during decoding, \textsc{MemDec} will read from this memory and write to this memory once, both with content-based addressing. Unlike the unbounded memory in previous work\cite{RNNsearch} to store the representation of source sentence, the memory in \textsc{MemDec} is a matrix with pre-determined size designed to better capture the information important for the decoding process at each time step. Our empirical study on Chinese-English translation shows that it can improve by $4.8$ BLEU upon Groundhog and $5.3$ BLEU upon on Moses, yielding the best performance achieved with the same training set.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.02003](https://arxiv.org/abs/1606.02003)

##### PDF
[https://arxiv.org/pdf/1606.02003](https://arxiv.org/pdf/1606.02003)

