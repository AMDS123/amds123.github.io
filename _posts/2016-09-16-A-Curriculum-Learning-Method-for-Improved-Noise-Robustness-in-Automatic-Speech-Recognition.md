---
layout: post
title: "A Curriculum Learning Method for Improved Noise Robustness in Automatic Speech Recognition"
date: 2016-09-16 15:20:39
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Optimization Recognition
author: Stefan Braun, Daniel Neil, Shih-Chii Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of automatic speech recognition systems under noisy environments still leaves room for improvement. Speech enhancement or feature enhancement techniques for increasing noise robustness of these systems usually add components to the recognition system that need careful optimization. In this work, we propose the use of a relatively simple curriculum training strategy called accordion annealing (ACCAN). It uses a multi-stage training schedule where samples at signal-to-noise ratio (SNR) values as low as 0dB are first added and samples at increasing higher SNR values are gradually added up to an SNR value of 50dB. We also use a method called per-epoch noise mixing (PEM) that generates noisy training samples online during training and thus enables dynamically changing the SNR of our training data. Both the ACCAN and the PEM methods are evaluated on a end-to-end speech recognition pipeline on the Wall Street Journal corpus. ACCAN decreases the average word error rate (WER) on the 20dB to -10dB SNR range by up to 31.4% when compared to a conventional multi-condition training method.

##### Abstract (translated by Google)
自动语音识别系统在噪声环境下的性能还有待改进。用于增加这些系统的噪声鲁棒性的语音增强或特征增强技术通常将元件添加到需要仔细优化的识别系统。在这项工作中，我们建议使用一种称为手风琴退火（ACCAN）的相对简单的课程培训策略。它使用多阶段训练计划，其中首先将信噪比（SNR）值低至0dB的样本添加，并且将逐渐增加的较高SNR值的样本逐渐累加至50dB的SNR值。我们还使用一种称为per-epoch noise mixing（per-epoch noise mixing）的方法，在训练期间在线生成噪声训练样本，从而动态改变训练数据的SNR。 ACCAN和PEM方法都是在华尔街日报语料库的端对端语音识别流水线上评估的。与传统的多条件训练方法相比，ACCAN将20dB到-10dB的SNR范围内的平均字错误率（WER）降低高达31.4％。

##### URL
[https://arxiv.org/abs/1606.06864](https://arxiv.org/abs/1606.06864)

##### PDF
[https://arxiv.org/pdf/1606.06864](https://arxiv.org/pdf/1606.06864)

