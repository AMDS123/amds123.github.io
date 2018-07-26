---
layout: post
title: "Acoustic-to-Word Recognition with Sequence-to-Sequence Models"
date: 2018-07-23 06:29:43
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Language_Model Recognition
author: Shruti Palaskar, Florian Metze
mathjax: true
---

* content
{:toc}

##### Abstract
Acoustic-to-Word recognition provides a straightforward solution to end-to-end speech recognition without needing external decoding, language model re-scoring or lexicon. While character-based models offer a natural solution to the out-of-vocabulary problem, word models can be simpler to decode and may also be able to directly recognize semantically meaningful units. We present effective methods to train Sequence-to-Sequence models for direct word-level recognition (and character-level recognition) and show an absolute improvement of 4.4-5.0\% in Word Error Rate on the Switchboard corpus compared to prior work. In addition to these promising results, word-based models are more interpretable than character models, which have to be composed into words using a separate decoding step. We analyze the encoder hidden states and the attention behavior, and show that location-aware attention naturally represents words as a single speech-word-vector, despite spanning multiple frames in the input. We finally show that the Acoustic-to-Word model also learns to segment speech into words with a mean standard deviation of 3 frames as compared with human annotated forced-alignments for the Switchboard corpus.

##### Abstract (translated by Google)
声学到单词识别为端到端语音识别提供了直接的解决方案，无需外部解码，语言模型重新评分或词典。虽然基于字符的模型为词汇外问题提供了自然的解决方案，但是单词模型可以更简单地解码，并且还可以直接识别语义上有意义的单元。我们提出了有效的方法来训练用于直接词级识别（和字符级识别）的序列到序列模型，并且与先前的工作相比，在交换机语料库中的Word错误率中显示出4.4-5.0％的绝对改进。除了这些有希望的结果之外，基于单词的模型比字符模型更易于理解，字符模型必须使用单独的解码步骤组成单词。我们分析编码器隐藏状态和注意行为，并且表明位置感知注意自然地将单词表示为单个语音 - 单词 - 向量，尽管在输入中跨越多个帧。我们最终表明，与用于Switchboard语料库的人类注释强制对齐相比，Acoustic-to-Word模型还学习将语音分段为平均标准差为3帧的单词。

##### URL
[http://arxiv.org/abs/1807.09597](http://arxiv.org/abs/1807.09597)

##### PDF
[http://arxiv.org/pdf/1807.09597](http://arxiv.org/pdf/1807.09597)

