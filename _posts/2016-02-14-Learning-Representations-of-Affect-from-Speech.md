---
layout: post
title: "Learning Representations of Affect from Speech"
date: 2016-02-14 18:11:46
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Represenation_Learning RNN Classification Recognition
author: Sayan Ghosh, Eugene Laksana, Louis-Philippe Morency, Stefan Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
There has been a lot of prior work on representation learning for speech recognition applications, but not much emphasis has been given to an investigation of effective representations of affect from speech, where the paralinguistic elements of speech are separated out from the verbal content. In this paper, we explore denoising autoencoders for learning paralinguistic attributes i.e. categorical and dimensional affective traits from speech. We show that the representations learnt by the bottleneck layer of the autoencoder are highly discriminative of activation intensity and at separating out negative valence (sadness and anger) from positive valence (happiness). We experiment with different input speech features (such as FFT and log-mel spectrograms with temporal context windows), and different autoencoder architectures (such as stacked and deep autoencoders). We also learn utterance specific representations by a combination of denoising autoencoders and BLSTM based recurrent autoencoders. Emotion classification is performed with the learnt temporal/dynamic representations to evaluate the quality of the representations. Experiments on a well-established real-life speech dataset (IEMOCAP) show that the learnt representations are comparable to state of the art feature extractors (such as voice quality features and MFCCs) and are competitive with state-of-the-art approaches at emotion and dimensional affect recognition.

##### Abstract (translated by Google)
在语音识别应用的表示学习方面有很多先前的工作，但没有太多的重点研究有效的言语情感表征，其中言语的辅助语言元素从言语内容中分离出来。在本文中，我们探索去噪自动编码器，用于学习语言的辅助语言属性，即分类和维度情感特征。我们证明自动编码器的瓶颈层所学到的表示是高度区分激活强度和从正价（幸福）中分离出负价（悲伤和愤怒）。我们使用不同的输入语音特征（例如带有时间上下文窗口的FFT和log-mel谱图）以及不同的自动编码器体系结构（如堆栈和深度自动编码器）进行实验。我们还通过去噪自动编码器和基于BLSTM的循环自动编码器的组合来学习话语特定的表示。情绪分类是利用所学习的时间/动态表示进行的，以评估表示的质量。在完善的现实生活语音数据集（IEMOCAP）上的实验表明，所学习的表示与现有技术的特征提取器（如语音质量特征和MFCC）相当，并且与最先进的方法情感和维度影响识别。

##### URL
[https://arxiv.org/abs/1511.04747](https://arxiv.org/abs/1511.04747)

##### PDF
[https://arxiv.org/pdf/1511.04747](https://arxiv.org/pdf/1511.04747)

