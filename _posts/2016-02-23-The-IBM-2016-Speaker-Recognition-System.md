---
layout: post
title: "The IBM 2016 Speaker Recognition System"
date: 2016-02-23 20:39:40
categories: arXiv_SD
tags: arXiv_SD Knowledge Speech_Recognition Recognition
author: Seyed Omid Sadjadi, Sriram Ganapathy, Jason W. Pelecanos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we describe the recent advancements made in the IBM i-vector speaker recognition system for conversational speech. In particular, we identify key techniques that contribute to significant improvements in performance of our system, and quantify their contributions. The techniques include: 1) a nearest-neighbor discriminant analysis (NDA) approach that is formulated to alleviate some of the limitations associated with the conventional linear discriminant analysis (LDA) that assumes Gaussian class-conditional distributions, 2) the application of speaker- and channel-adapted features, which are derived from an automatic speech recognition (ASR) system, for speaker recognition, and 3) the use of a deep neural network (DNN) acoustic model with a large number of output units (~10k senones) to compute the frame-level soft alignments required in the i-vector estimation process. We evaluate these techniques on the NIST 2010 speaker recognition evaluation (SRE) extended core conditions involving telephone and microphone trials. Experimental results indicate that: 1) the NDA is more effective (up to 35% relative improvement in terms of EER) than the traditional parametric LDA for speaker recognition, 2) when compared to raw acoustic features (e.g., MFCCs), the ASR speaker-adapted features provide gains in speaker recognition performance, and 3) increasing the number of output units in the DNN acoustic model (i.e., increasing the senone set size from 2k to 10k) provides consistent improvements in performance (for example from 37% to 57% relative EER gains over our baseline GMM i-vector system). To our knowledge, results reported in this paper represent the best performances published to date on the NIST SRE 2010 extended core tasks.

##### Abstract (translated by Google)
在本文中，我们描述了IBM i矢量说话人识别系统中对话语音的最新进展。特别是，我们确定有助于显着提高系统性能的关键技术，并量化其贡献。该技术包括：1）最近邻判别分析（NDA）方法，其被制定用于减轻与假定高斯类别条件分布的常规线性判别分析（LDA）相关的一些局限性; 2）和用于说话人识别的从自动语音识别（ASR）系统导出的信道自适应特征，以及3）使用具有大量输出单元（〜10k个语音）的深度神经网络（DNN）声学模型，以计算i矢量估计过程中所需的帧级软对准。我们评估这些技术在2010年美国国家标准与技术研究所（NIST）的说话人识别评估（SRE）扩展核心条件涉及电话和麦克风试验实验结果表明：1）对于说话人识别，NDA比传统的参数化LDA更有效（相对于EER改善35％）; 2）与原始声学特征（例如MFCC）相比，ASR扬声器适应性特征提高了说话者识别性能，并且3）在DNN声学模型中增加输出单元的数量（即，将句音集合的大小从2k增加到10k）提供了一致的性能改善（例如从37％到57相对于我们的基线GMM i-矢量系统的相对EER收益）。就我们所知，本文中报告的结果代表了NIST SRE 2010扩展核心任务迄今为止发布的最佳性能。

##### URL
[https://arxiv.org/abs/1602.07291](https://arxiv.org/abs/1602.07291)

##### PDF
[https://arxiv.org/pdf/1602.07291](https://arxiv.org/pdf/1602.07291)

