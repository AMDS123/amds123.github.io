---
layout: post
title: "Jointly Aligning and Predicting Continuous Emotion Annotations"
date: 2019-07-05 23:49:49
categories: arXiv_AI
tags: arXiv_AI CNN
author: Soheil Khorram, Melvin G McInnis, Emily Mower Provost
mathjax: true
---

* content
{:toc}

##### Abstract
Time-continuous dimensional descriptions of emotions (e.g., arousal, valence) allow researchers to characterize short-time changes and to capture long-term trends in emotion expression. However, continuous emotion labels are generally not synchronized with the input speech signal due to delays caused by reaction-time, which is inherent in human evaluations. To deal with this challenge, we introduce a new convolutional neural network (multi-delay sinc network) that is able to simultaneously align and predict labels in an end-to-end manner. The proposed network is a stack of convolutional layers followed by an aligner network that aligns the speech signal and emotion labels. This network is implemented using a new convolutional layer that we introduce, the delayed sinc layer. It is a time-shifted low-pass (sinc) filter that uses a gradient-based algorithm to learn a single delay. Multiple delayed sinc layers can be used to compensate for a non-stationary delay that is a function of the acoustic space. We test the efficacy of this system on two common emotion datasets, RECOLA and SEWA, and show that this approach obtains state-of-the-art speech-only results by learning time-varying delays while predicting dimensional descriptors of emotions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03050](http://arxiv.org/abs/1907.03050)

##### PDF
[http://arxiv.org/pdf/1907.03050](http://arxiv.org/pdf/1907.03050)

