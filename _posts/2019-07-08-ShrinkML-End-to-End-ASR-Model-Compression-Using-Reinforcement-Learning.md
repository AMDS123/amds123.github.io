---
layout: post
title: "ShrinkML: End-to-End ASR Model Compression Using Reinforcement Learning"
date: 2019-07-08 12:10:18
categories: arXiv_AI
tags: arXiv_AI Attention Speech_Recognition Reinforcement_Learning RNN Recognition
author: &#x141;ukasz Dudziak, Mohamed S. Abdelfattah, Ravichander Vipperla, Stefanos Laskaridis, Nicholas D. Lane
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end automatic speech recognition (ASR) models are increasingly large and complex to achieve the best possible accuracy. In this paper, we build an AutoML system that uses reinforcement learning (RL) to optimize the per-layer compression ratios when applied to a state-of-the-art attention based end-to-end ASR model composed of several LSTM layers. We use singular value decomposition (SVD) low-rank matrix factorization as the compression method. For our RL-based AutoML system, we focus on practical considerations such as the choice of the reward/punishment functions, the formation of an effective search space, and the creation of a representative but small data set for quick evaluation between search steps. Finally, we present accuracy results on LibriSpeech of the model compressed by our AutoML system, and we compare it to manually-compressed models. Our results show that in the absence of retraining our RL-based search is an effective and practical method to compress a production-grade ASR system. When retraining is possible, we show that our AutoML system can select better highly-compressed seed models compared to manually hand-crafted rank selection, thus allowing for more compression than previously possible.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03540](http://arxiv.org/abs/1907.03540)

##### PDF
[http://arxiv.org/pdf/1907.03540](http://arxiv.org/pdf/1907.03540)

