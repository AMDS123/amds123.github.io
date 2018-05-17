---
layout: post
title: "A Comparison of Modeling Units in Sequence-to-Sequence Speech Recognition with the Transformer on Mandarin Chinese"
date: 2018-05-16 10:43:47
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Language_Model Recognition
author: Shiyu Zhou, Linhao Dong, Shuang Xu, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
The choice of modeling units is critical to automatic speech recognition (ASR) tasks. Conventional ASR systems typically choose context-dependent states (CD-states) or context-dependent phonemes (CD-phonemes) as their modeling units. However, it has been challenged by sequence-to-sequence attention-based models, which integrate an acoustic, pronunciation and language model into a single neural network. On English ASR tasks, previous attempts have shown that the modeling unit of graphemes can outperform that of phonemes by sequence-to-sequence attention-based model. 
 In this paper, we are concerned with modeling units on Mandarin Chinese ASR tasks using sequence-to-sequence attention-based models with the Transformer. Five modeling units are explored including context-independent phonemes (CI-phonemes), syllables, words, sub-words and characters. Experiments on HKUST datasets demonstrate that the lexicon free modeling units can outperform lexicon related modeling units in terms of character error rate (CER). Among five modeling units, character based model performs best and establishes a new state-of-the-art CER of \emph{$26.64\%$} on HKUST datasets without a hand-designed lexicon and an extra language model integration, which corresponds to a \emph{$4.8\%$} relative improvement over the existing best CER of $28.0\%$ by the joint CTC-attention based encoder-decoder network.

##### Abstract (translated by Google)
建模单元的选择对自动语音识别（ASR）任务至关重要。传统的ASR系统通常选择上下文相关状态（CD状态）或上下文相关音素（CD音素）作为其建模单元。然而，它受到从序列到序列注意的模型的挑战，该模型将声学，发音和语言模型集成到单个神经网络中。在英语ASR任务中，以前的尝试表明，通过序列到序列注意模型，字形的建模单元可以超越音素的建模单元。
 在本文中，我们关注的是使用Transformer的序列到序列注意模型来建立汉语普通话ASR任务的建模单元。探索五个建模单元，包括与上下文无关的音素（CI音素），音节，单词，子词和字符。 HKUST数据集上的实验表明，无论词典的建模单元在字符错误率（CER）方面的表现都优于词典相关的建模单元。在五个建模单元中，基于字符的模型表现最佳，并且在HKUST数据集上建立了一个新的最先进的CER {$ 26.64 \％$} CER，没有手工设计的词典和额外的语言模型集成，对应通过联合CTC注意的编码器 - 解码器网络，相对于现有的最佳CER $ 28.0 \％$的相对改进$ {$ 4.8 \％$}。

##### URL
[http://arxiv.org/abs/1805.06239](http://arxiv.org/abs/1805.06239)

##### PDF
[http://arxiv.org/pdf/1805.06239](http://arxiv.org/pdf/1805.06239)

