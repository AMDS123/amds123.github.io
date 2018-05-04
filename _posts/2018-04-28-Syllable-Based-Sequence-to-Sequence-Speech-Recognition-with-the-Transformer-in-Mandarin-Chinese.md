---
layout: post
title: "Syllable-Based Sequence-to-Sequence Speech Recognition with the Transformer in Mandarin Chinese"
date: 2018-04-28 06:54:11
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition NMT RNN Language_Model Recognition
author: Shiyu Zhou, Linhao Dong, Shuang Xu, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence attention-based models have recently shown very promising results on automatic speech recognition (ASR) tasks, which integrate an acoustic, pronunciation and language model into a single neural network. In these models, the Transformer, a new sequence-to-sequence attention-based model relying entirely on self-attention without using RNNs or convolutions, achieves a new single-model state-of-the-art BLEU on neural machine translation (NMT) tasks. Since the outstanding performance of the Transformer, we extend it to speech and concentrate on it as the basic architecture of sequence-to-sequence attention-based model on Mandarin Chinese ASR tasks. Furthermore, we investigate a comparison between syllable based model and context-independent phoneme (CI-phoneme) based model with the Transformer in Mandarin Chinese. Additionally, a greedy cascading decoder with the Transformer is proposed for mapping CI-phoneme sequences and syllable sequences into word sequences. Experiments on HKUST datasets demonstrate that syllable based model with the Transformer performs better than CI-phoneme based counterpart, and achieves a character error rate (CER) of \emph{$28.77\%$}, which is competitive to the state-of-the-art CER of $28.0\%$ by the joint CTC-attention based encoder-decoder network.

##### Abstract (translated by Google)
基于序列注意的模型最近在自动语音识别（ASR）任务中显示出非常有希望的结果，该任务将声学，发音和语言模型集成到单个神经网络中。在这些模型中，Transformer是一种新型的基于序列到序列注意的模型，完全依赖于自我注意而不使用RNN或卷积，从而实现了一种新的单模型最先进的神经机器翻译BLEU（NMT ） 任务。自从Transformer的出色表现以来，我们将其扩展到语音，并将其作为中文普通话ASR任务中从序列到序列注意模型的基本架构。此外，我们调查了基于音节的模型和基于上下文无关音素（CI音素）的模型与Transformer在汉语中的比较。此外，还提出了一种具有Transformer的贪心级联解码器，用于将CI音素序列和音节序列映射为单词序列。对HKUST数据集进行的实验表明，基于音节的Transformer模型比基于CI音素的模型表现更好，并且实现了\ emph {$ 28.77 \％$}的字符错误率（CER），这对于状态 - 基于联合CTC注意力的编码器 - 解码器网络的$ 28.0 \％$-CER。

##### URL
[https://arxiv.org/abs/1804.10752](https://arxiv.org/abs/1804.10752)

##### PDF
[https://arxiv.org/pdf/1804.10752](https://arxiv.org/pdf/1804.10752)

