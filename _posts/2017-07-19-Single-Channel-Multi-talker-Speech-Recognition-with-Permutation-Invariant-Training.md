---
layout: post
title: "Single-Channel Multi-talker Speech Recognition with Permutation Invariant Training"
date: 2017-07-19 03:48:54
categories: arXiv_CL
tags: arXiv_CL Knowledge GAN Speech_Recognition Deep_Learning Recognition
author: Yanmin Qian, Xuankai Chang, Dong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Although great progresses have been made in automatic speech recognition (ASR), significant performance degradation is still observed when recognizing multi-talker mixed speech. In this paper, we propose and evaluate several architectures to address this problem under the assumption that only a single channel of mixed signal is available. Our technique extends permutation invariant training (PIT) by introducing the front-end feature separation module with the minimum mean square error (MSE) criterion and the back-end recognition module with the minimum cross entropy (CE) criterion. More specifically, during training we compute the average MSE or CE over the whole utterance for each possible utterance-level output-target assignment, pick the one with the minimum MSE or CE, and optimize for that assignment. This strategy elegantly solves the label permutation problem observed in the deep learning based multi-talker mixed speech separation and recognition systems. The proposed architectures are evaluated and compared on an artificially mixed AMI dataset with both two- and three-talker mixed speech. The experimental results indicate that our proposed architectures can cut the word error rate (WER) by 45.0% and 25.0% relatively against the state-of-the-art single-talker speech recognition system across all speakers when their energies are comparable, for two- and three-talker mixed speech, respectively. To our knowledge, this is the first work on the multi-talker mixed speech recognition on the challenging speaker-independent spontaneous large vocabulary continuous speech task.

##### Abstract (translated by Google)
在自动语音识别（ASR）方面虽然取得了很大的进展，但在识别多方说话人混合语音时仍然存在明显的性能下降。在本文中，我们提出并评估了几种体系结构，以在假定只有单个信道的混合信号可用的情况下解决这个问题。我们的技术通过引入具有最小均方误差（MSE）准则的前端特征分离模块和具有最小交叉熵（CE）准则的后端识别模块来延伸置换不变量训练（PIT）。更具体地说，在训练期间，我们针对每个可能的发声级输出 - 目标分配计算整个话语上的平均MSE或CE，选择具有最小MSE或CE的那个，并针对该分配进行优化。该策略优雅地解决了在基于深度学习的多讲话者混合语音分离和识别系统中观察到的标签置换问题。所提出的体系结构在人工混合的AMI数据集上与两个和三个讲话者的混合语音进行评估和比较。实验结果表明，我们提出的体系结构可以将所有说话人的语义错误率（WER）相对于最先进的单个说话人语音识别系统在能量可比的情况下相对减少45.0％和25.0％和三言两语混合演讲。就我们所知，这是第一部针对具有挑战性的与说话人无关的自发性大词汇量连续语音任务的多说话人混合语音识别。

##### URL
[https://arxiv.org/abs/1707.06527](https://arxiv.org/abs/1707.06527)

##### PDF
[https://arxiv.org/pdf/1707.06527](https://arxiv.org/pdf/1707.06527)

