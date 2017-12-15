---
layout: post
title: "Multitask Learning with CTC and Segmental CRF for Speech Recognition"
date: 2017-06-05 18:19:34
categories: arXiv_SD
tags: arXiv_SD Segmentation Speech_Recognition RNN Classification Recognition
author: Liang Lu, Lingpeng Kong, Chris Dyer, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Segmental conditional random fields (SCRFs) and connectionist temporal classification (CTC) are two sequence labeling methods used for end-to-end training of speech recognition models. Both models define a transcription probability by marginalizing decisions about latent segmentation alternatives to derive a sequence probability: the former uses a globally normalized joint model of segment labels and durations, and the latter classifies each frame as either an output symbol or a "continuation" of the previous label. In this paper, we train a recognition model by optimizing an interpolation between the SCRF and CTC losses, where the same recurrent neural network (RNN) encoder is used for feature extraction for both outputs. We find that this multitask objective improves recognition accuracy when decoding with either the SCRF or CTC models. Additionally, we show that CTC can also be used to pretrain the RNN encoder, which improves the convergence rate when learning the joint model.

##### Abstract (translated by Google)
分段条件随机场（SCRF）和联结主义时间分类（CTC）是两种序列标记方法，用于语音识别模型的端到端训练。两种模型通过边际化潜在分割选择的决定来定义转录概率，以得出序列概率：前者使用片段标签和持续时间的全局标准化联合模型，而后者将每个帧分类为输出符号或者“延续”之前的标签。在本文中，我们通过优化SCRF和CTC损耗之间的插值来训练识别模型，其中使用相同的递归神经网络（RNN）编码器来对两个输出进行特征提取。我们发现，这个多任务目标提高了SCRF或CTC模型解码时的识别精度。此外，我们还表明，CTC也可以用来预编码RNN，从而提高了学习联合模型时的收敛速度。

##### URL
[https://arxiv.org/abs/1702.06378](https://arxiv.org/abs/1702.06378)

##### PDF
[https://arxiv.org/pdf/1702.06378](https://arxiv.org/pdf/1702.06378)

