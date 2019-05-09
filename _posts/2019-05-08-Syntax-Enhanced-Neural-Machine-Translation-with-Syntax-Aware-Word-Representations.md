---
layout: post
title: "Syntax-Enhanced Neural Machine Translation with Syntax-Aware Word Representations"
date: 2019-05-08 02:56:43
categories: arXiv_CL
tags: arXiv_CL Embedding NMT RNN
author: Meishan Zhang, Zhenghua Li, Guohong Fu, Min Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Syntax has been demonstrated highly effective in neural machine translation (NMT). Previous NMT models integrate syntax by representing 1-best tree outputs from a well-trained parsing system, e.g., the representative Tree-RNN and Tree-Linearization methods, which may suffer from error propagation. In this work, we propose a novel method to integrate source-side syntax implicitly for NMT. The basic idea is to use the intermediate hidden representations of a well-trained end-to-end dependency parser, which are referred to as syntax-aware word representations (SAWRs). Then, we simply concatenate such SAWRs with ordinary word embeddings to enhance basic NMT models. The method can be straightforwardly integrated into the widely-used sequence-to-sequence (Seq2Seq) NMT models. We start with a representative RNN-based Seq2Seq baseline system, and test the effectiveness of our proposed method on two benchmark datasets of the Chinese-English and English-Vietnamese translation tasks, respectively. Experimental results show that the proposed approach is able to bring significant BLEU score improvements on the two datasets compared with the baseline, 1.74 points for Chinese-English translation and 0.80 point for English-Vietnamese translation, respectively. In addition, the approach also outperforms the explicit Tree-RNN and Tree-Linearization methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02878](http://arxiv.org/abs/1905.02878)

##### PDF
[http://arxiv.org/pdf/1905.02878](http://arxiv.org/pdf/1905.02878)

