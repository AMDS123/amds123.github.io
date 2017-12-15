---
layout: post
title: "VoiceLoop: Voice Fitting and Synthesis via a Phonological Loop"
date: 2017-10-27 15:29:44
categories: arXiv_CL
tags: arXiv_CL Attention
author: Yaniv Taigman, Lior Wolf, Adam Polyak, Eliya Nachmani
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new neural text to speech (TTS) method that is able to transform text to speech in voices that are sampled in the wild. Unlike other systems, our solution is able to deal with unconstrained voice samples and without requiring aligned phonemes or linguistic features. The network architecture is simpler than those in the existing literature and is based on a novel shifting buffer working memory. The same buffer is used for estimating the attention, computing the output audio, and for updating the buffer itself. The input sentence is encoded using a context-free lookup table that contains one entry per character or phoneme. The speakers are similarly represented by a short vector that can also be fitted to new identities, even with only a few samples. Variability in the generated speech is achieved by priming the buffer prior to generating the audio. Experimental results on several datasets demonstrate convincing capabilities, making TTS accessible to a wider range of applications. In order to promote reproducibility, we release our source code and models.

##### Abstract (translated by Google)
我们提出了一种新的神经文本到语音（TTS）方法，能够将文本转换成在野外采样的语音。与其他系统不同，我们的解决方案能够处理不受约束的语音样本，而不需要对齐音素或语言特征。网络结构比现有文献中的结构简单，并且基于新颖的移位缓冲器工作存储器。使用相同的缓冲区来估计注意力，计算输出音频以及更新缓冲区本身。输入句子使用上下文无关的查找表进行编码，该查找表包含每个字符或音素的一个条目。扬声器也可以用一个短的矢量表示，即使只有少数样本也可以适应新的身份。生成语音的变化是通过在生成音频之前启动缓冲区来实现的。几个数据集上的实验结果证明了令人信服的能力，使得TTS可以被更广泛的应用访问。为了提高可重复性，我们发布我们的源代码和模型。

##### URL
[https://arxiv.org/abs/1707.06588](https://arxiv.org/abs/1707.06588)

##### PDF
[https://arxiv.org/pdf/1707.06588](https://arxiv.org/pdf/1707.06588)

