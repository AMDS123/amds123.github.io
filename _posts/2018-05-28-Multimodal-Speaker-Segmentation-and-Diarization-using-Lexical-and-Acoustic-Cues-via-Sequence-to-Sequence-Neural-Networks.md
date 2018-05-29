---
layout: post
title: "Multimodal Speaker Segmentation and Diarization using Lexical and Acoustic Cues via Sequence to Sequence Neural Networks"
date: 2018-05-28 01:58:55
categories: arXiv_SD
tags: arXiv_SD Segmentation Speech_Recognition Recognition
author: Tae Jin Park, Panayiotis Georgiou
mathjax: true
---

* content
{:toc}

##### Abstract
While there has been substantial amount of work in speaker diarization recently, there are few efforts in jointly employing lexical and acoustic information for speaker segmentation. Towards that, we investigate a speaker diarization system using a sequence-to-sequence neural network trained on both lexical and acoustic features. We also propose a loss function that allows for selecting not only the speaker change points but also the best speaker at any time by allowing for different speaker groupings. We incorporate Mel Frequency Cepstral Coefficients (MFCC) as an acoustic feature alongside lexical information that are obtained from conversations from the Fisher dataset. Thus, we show that acoustics provide complementary information to the lexical modality. The experimental results show that sequence-to-sequence system trained on both word sequences and MFCC can improve on speaker diarization result compared to the system that only relies on lexical modality or the baseline MFCC-based system. In addition, we test the performance of our proposed method with Automatic Speech Recognition (ASR) transcripts. While the performance on ASR transcripts drops, the Diarization Error Rate (DER) of our proposed method still outperforms the traditional method based on Bayesian Information Criterion (BIC).

##### Abstract (translated by Google)
虽然最近在演讲者diarization方面进行了大量工作，但在为演讲者分割联合使用词汇和声学信息方面却很少做出努力。为此，我们使用在词汇和声学特征上训练的序列 - 序列神经网络来研究说话者diarization系统。我们还提出了一个损失函数，通过允许不同的演讲者分组，可以随时选择演讲者变化点，也可以选择最佳演讲者。我们将梅尔频率倒谱系数（MFCC）作为一个声学特征与从Fisher数据集的对话中获得的词汇信息结合在一起。因此，我们表明声学为词汇形式提供了补充信息。实验结果表明，与仅依赖词汇模态或基于MFCC的基线系统相比，在单词序列和MFCC上训练的序列到序列系统可以改善说话者的二化结果。另外，我们用自动语音识别（ASR）成绩单来测试我们提出的方法的性能。虽然ASR转录本的性能下降，但我们提出的方法的Diarization Error Rate（DER）仍然优于基于贝叶斯信息准则（BIC）的传统方法。

##### URL
[http://arxiv.org/abs/1805.10731](http://arxiv.org/abs/1805.10731)

##### PDF
[http://arxiv.org/pdf/1805.10731](http://arxiv.org/pdf/1805.10731)

