---
layout: post
title: "Information Theoretic Analysis of DNN-HMM Acoustic Modeling"
date: 2017-11-08 15:52:53
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Quantitative Recognition
author: Pranay Dighe, Afsaneh Asaei, Hervé Bourlard
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an information theoretic framework for quantitative assessment of acoustic modeling for hidden Markov model (HMM) based automatic speech recognition (ASR). Acoustic modeling yields the probabilities of HMM sub-word states for a short temporal window of speech acoustic features. We cast ASR as a communication channel where the input sub-word probabilities convey the information about the output HMM state sequence. The quality of the acoustic model is thus quantified in terms of the information transmitted through this channel. The process of inferring the most likely HMM state sequence from the sub-word probabilities is known as decoding. HMM based decoding assumes that an acoustic model yields accurate state-level probabilities and the data distribution given the underlying hidden state is independent of any other state in the sequence. We quantify 1) the acoustic model accuracy and 2) its robustness to mismatch between data and the HMM conditional independence assumption in terms of some mutual information quantities. In this context, exploiting deep neural network (DNN) posterior probabilities leads to a simple and straightforward analysis framework to assess shortcomings of the acoustic model for HMM based decoding. This analysis enables us to evaluate the Gaussian mixture acoustic model (GMM) and the importance of many hidden layers in DNNs without any need of explicit speech recognition. In addition, it sheds light on the contribution of low-dimensional models to enhance acoustic modeling for better compliance with the HMM based decoding requirements.

##### Abstract (translated by Google)
我们提出了一个基于隐马尔可夫模型（HMM）的自动语音识别（ASR）声学建模定量评估信息理论框架。声学建模为语音声学特征的短暂时间窗口产生HMM子字状态的概率。我们把ASR作为一个通信通道，输入子字概率传达输出HMM状态序列的信息。声学模型的质量就是通过这个通道传输的信息量化的。从子字概率推断最有可能的HMM状态序列的过程称为解码。基于HMM的解码假定声学模型产生准确的状态级概率，给定隐藏状态的数据分布独立于序列中的任何其他状态。我们量化1）声学模型的准确性和2）其对数据和HMM条件独立假设之间的失配的一些互信息量的鲁棒性。在这种情况下，利用深度神经网络（DNN）后验概率导致简单和直接的分析框架来评估基于HMM的解码的声学模型的缺点。这种分析使我们能够评估高斯混合声学模型（GMM）和DNN中的许多隐藏层的重要性，而不需要任何明确的语音识别。此外，它揭示了低维模型对增强声学建模的贡献，以更好地符合基于HMM的解码要求。

##### URL
[https://arxiv.org/abs/1709.01144](https://arxiv.org/abs/1709.01144)

##### PDF
[https://arxiv.org/e-print/1709.01144](https://arxiv.org/e-print/1709.01144)

