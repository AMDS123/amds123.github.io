---
layout: post
title: "End-to-end Audiovisual Speech Recognition"
date: 2018-02-18 19:07:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Speech_Recognition Classification Deep_Learning Recognition
author: Stavros Petridis, Themos Stafylakis, Pingchuan Ma, Feipeng Cai, Georgios Tzimiropoulos, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Several end-to-end deep learning approaches have been recently presented which extract either audio or visual features from the input images or audio signals and perform speech recognition. However, research on end-to-end audiovisual models is very limited. In this work, we present an end-to-end audiovisual model based on residual networks and Bidirectional Gated Recurrent Units (BGRUs). To the best of our knowledge, this is the first audiovisual fusion model which simultaneously learns to extract features directly from the image pixels and audio waveforms and performs within-context word recognition on a large publicly available dataset (LRW). The model consists of two streams, one for each modality, which extract features directly from mouth regions and raw waveforms. The temporal dynamics in each stream/modality are modeled by a 2-layer BGRU and the fusion of multiple streams/modalities takes place via another 2-layer BGRU. A slight improvement in the classification rate over an end-to-end audio-only and MFCC-based model is reported in clean audio conditions and low levels of noise. In presence of high levels of noise, the end-to-end audiovisual model significantly outperforms both audio-only models.

##### Abstract (translated by Google)
近来已经提出了几种端到端深度学习方法，其从输入图像或音频信号中提取音频或视觉特征并执行语音识别。但是，端到端视听模型的研究非常有限。在这项工作中，我们提出了一个基于残余网络和双向门控循环单元（BGRU）的端到端视听模型。就我们所知，这是第一个同时学习从图像像素和音频波形直接提取特征并在大型公开可用数据集（LRW）上执行内部词语识别的视听融合模型。该模型由两个流组成，一个用于每个模态，从口区和原始波形直接提取特征。每个流/模态中的时间动态模型由2层BGRU建模，并且多个流/模态的融合通过另一个2层BGRU进行。在干净的音频条件和较低的噪音水平下，报告了端到端纯音频和基于MFCC的模型的分类率略有提高。在高噪音环境中，端到端视听模式明显优于两个纯音频模型。

##### URL
[http://arxiv.org/abs/1802.06424](http://arxiv.org/abs/1802.06424)

##### PDF
[http://arxiv.org/pdf/1802.06424](http://arxiv.org/pdf/1802.06424)

