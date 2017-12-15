---
layout: post
title: "Sequence-to-Sequence Models Can Directly Translate Foreign Speech"
date: 2017-06-12 13:54:12
categories: arXiv_SD
tags: arXiv_SD Attention Speech_Recognition Recognition
author: Ron J. Weiss, Jan Chorowski, Navdeep Jaitly, Yonghui Wu, Zhifeng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a recurrent encoder-decoder deep neural network architecture that directly translates speech in one language into text in another. The model does not explicitly transcribe the speech into text in the source language, nor does it require supervision from the ground truth source language transcription during training. We apply a slightly modified sequence-to-sequence with attention architecture that has previously been used for speech recognition and show that it can be repurposed for this more complex task, illustrating the power of attention-based models. A single model trained end-to-end obtains state-of-the-art performance on the Fisher Callhome Spanish-English speech translation task, outperforming a cascade of independently trained sequence-to-sequence speech recognition and machine translation models by 1.8 BLEU points on the Fisher test set. In addition, we find that making use of the training data in both languages by multi-task training sequence-to-sequence speech translation and recognition models with a shared encoder network can improve performance by a further 1.4 BLEU points.

##### Abstract (translated by Google)
我们提出了一种经常使用的编码器 - 解码器深层神经网络架构，它将一种语言的语言直接翻译成另一种语言的文本。该模型没有明确地将语言转换成源语言的文本，也不需要在训练过程中从地面真值源语言转录中进行监督。我们对以前用于语音识别的注意结构应用了稍微修改的序列到序列，并且表明它可以用于这个更复杂的任务，说明基于注意的模型的强大功能。 Fisher Callhome西班牙语 - 英语语音翻译任务中单端模式的端到端培训获得了最先进的性能，比单独训练的序列 - 语音序列级联语音识别和机器翻译模型级数高出1.8 BLEU点在费舍尔测试集上。另外，我们发现通过使用共享编码器网络的多任务训练序列 - 序列语音翻译和识别模型，利用两种语言的训练数据可以将性能提高1.4个BLEU点。

##### URL
[https://arxiv.org/abs/1703.08581](https://arxiv.org/abs/1703.08581)

##### PDF
[https://arxiv.org/pdf/1703.08581](https://arxiv.org/pdf/1703.08581)

