---
layout: post
title: "NRTR: A No-Recurrence Sequence-to-Sequence Model For Scene Text Recognition"
date: 2018-06-04 02:10:35
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Classification Recognition
author: Fenfen Sheng, Zhineng Chen, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text recognition has attracted a great many researches for decades due to its importance to various applications. Existing sequence-to-sequence (seq2seq) recognizers mainly adopt Connectionist Temporal Classification (CTC) or Attention based Recurrent or Convolutional networks, and have made great progresses in scene text recognition. However, we observe that current methods suffer from slow training speed because the internal recurrence of RNNs limits training parallelization, and high complexity because of stacking too many convolutional layers in order to extract features over long input sequence. To tackle the above problems, this paper presents a no-recurrence seq2seq model, named NRTR, that relies only on the attention mechanism dispensing with recurrences and convolutions entirely. NRTR consists of an encoder that transforms an input sequence to the hidden feature representation, and a decoder that generates an output sequence of characters from the encoder output. Both of the encoder and the decoder are based on self-attention module to learn positional dependencies, which could be trained with more parallelization and less complexity. Besides, we also propose a modality-transform block to effectively transform the input image to the corresponding sequence, which could be used by the encoder directly. NRTR is end-to-end trainable and is not confined to any predefined lexicon. Extensive experiments on various benchmarks, including the IIIT5K, SVT and ICDAR datasets, show that NRTR achieves the state-of-the-art or highly-competitive performances in both lexicon-free and lexicon-based scene text recognition tasks, while requiring only one order of magnitude less time for model training compared to current methods.

##### Abstract (translated by Google)
由于其对各种应用的重要性，场景文本识别已经数十年来吸引了许多研究。现有的序列到序列（seq2seq）识别器主要采用连接时间分类（CTC）或基于注意的递归或卷积网络，并且在场景文本识别中取得了很大进展。然而，我们观察到目前的方法遭受慢的训练速度，因为RNN的内部复发限制了训练并行化，并且由于叠加太多卷积层以便在长输入序列上提取特征而高度复杂化。针对上述问题，本文提出了一种不重复序列seq2seq模型，名为NRTR，它仅依赖于注意机制完全避免了循环和卷积。 NRTR由将输入序列变换为隐藏特征表示的编码器和从编码器输出产生字符输出序列的解码器组成。编码器和解码器都基于自我注意模块来学习位置依赖性，这可以通过更多的并行化和更少的复杂性来进行训练。此外，我们还提出了一种模态变换模块，将输入图像有效地转换为相应的序列，直接由编码器使用。 NRTR是端到端可训练的，并不局限于任何预定义的词典。包括IIIT5K，SVT和ICDAR数据集在内的各种基准测试的广泛实验表明，NRTR在基于词典和基于词典的场景文本识别任务中实现了最先进或高度竞争的性能，同时只需要一个与现有方法相比，模型训练的时间减少了数量级。

##### URL
[http://arxiv.org/abs/1806.00926](http://arxiv.org/abs/1806.00926)

##### PDF
[http://arxiv.org/pdf/1806.00926](http://arxiv.org/pdf/1806.00926)

