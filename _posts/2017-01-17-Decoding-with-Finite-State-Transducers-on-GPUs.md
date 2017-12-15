---
layout: post
title: "Decoding with Finite-State Transducers on GPUs"
date: 2017-01-17 14:48:24
categories: arXiv_SD
tags: arXiv_SD Knowledge Speech_Recognition Recognition
author: Arturo Argueta, David Chiang
mathjax: true
---

* content
{:toc}

##### Abstract
Weighted finite automata and transducers (including hidden Markov models and conditional random fields) are widely used in natural language processing (NLP) to perform tasks such as morphological analysis, part-of-speech tagging, chunking, named entity recognition, speech recognition, and others. Parallelizing finite state algorithms on graphics processing units (GPUs) would benefit many areas of NLP. Although researchers have implemented GPU versions of basic graph algorithms, limited previous work, to our knowledge, has been done on GPU algorithms for weighted finite automata. We introduce a GPU implementation of the Viterbi and forward-backward algorithm, achieving decoding speedups of up to 5.2x over our serial implementation running on different computer architectures and 6093x over OpenFST.

##### Abstract (translated by Google)
加权有限自动机和换能器（包括隐马尔可夫模型和条件随机场）被广泛应用于自然语言处理（NLP）中，以执行形态分析，词性标注，分块，命名实体识别，语音识别等任务。其他。并行化图形处理单元（GPU）上的有限状态算法将有利于NLP的许多领域。虽然研究人员已经实现了GPU版本的基本图算法，但是据我们所知，有限的以前的工作已经在加权有穷自动机的GPU算法上完成了。我们介绍了Viterbi和前向后向算法的GPU实现，通过在不同的计算机架构上运行的串行实现和在OpenFST上的6093x实现高达5.2倍的解码加速。

##### URL
[https://arxiv.org/abs/1701.03038](https://arxiv.org/abs/1701.03038)

##### PDF
[https://arxiv.org/pdf/1701.03038](https://arxiv.org/pdf/1701.03038)

