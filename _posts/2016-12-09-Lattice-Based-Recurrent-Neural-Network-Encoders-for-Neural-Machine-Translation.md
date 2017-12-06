---
layout: post
title: "Lattice-Based Recurrent Neural Network Encoders for Neural Machine Translation"
date: 2016-12-09 13:03:42
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Jinsong Su, Zhixing Tan, Deyi Xiong, Rongrong Ji, Xiaodong Shi, Yang Liu
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) heavily relies on word-level modelling to learn semantic representations of input sentences. However, for languages without natural word delimiters (e.g., Chinese) where input sentences have to be tokenized first, conventional NMT is confronted with two issues: 1) it is difficult to find an optimal tokenization granularity for source sentence modelling, and 2) errors in 1-best tokenizations may propagate to the encoder of NMT. To handle these issues, we propose word-lattice based Recurrent Neural Network (RNN) encoders for NMT, which generalize the standard RNN to word lattice topology. The proposed encoders take as input a word lattice that compactly encodes multiple tokenizations, and learn to generate new hidden states from arbitrarily many inputs and hidden states in preceding time steps. As such, the word-lattice based encoders not only alleviate the negative impact of tokenization errors but also are more expressive and flexible to embed input sentences. Experiment results on Chinese-English translation demonstrate the superiorities of the proposed encoders over the conventional encoder.

##### Abstract (translated by Google)
神经机器翻译（NMT）严重依赖于单词级建模来学习输入句子的语义表示。然而，对于没有自然词分界符（如中文）的语言，输入语句必须首先进行标记，常规NMT面临着两个问题：1）难以找到源语句建模的最佳标记粒度; 2）错误1的最佳标记可以传播到NMT的编码器。为了处理这些问题，我们提出了基于字 - 格的递归神经网络（NMN）编码器，将标准RNN推广到字格拓扑。所提出的编码器将输入字格作为输入，对多个标记进行紧凑编码，并学习在前面的时间步骤中从任意多的输入和隐藏状态中生成新的隐藏状态。同样，基于字格的编码器不仅减轻了标记误差的负面影响，而且嵌入输入句子更具有表达性和灵活性。汉英翻译的实验结果表明了所提出的编码器相对于传统编码器的优越性。

##### URL
[https://arxiv.org/abs/1609.07730](https://arxiv.org/abs/1609.07730)

