---
layout: post
title: "Low-Latency Deep Clustering For Speech Separation"
date: 2019-02-19 13:00:18
categories: arXiv_SD
tags: arXiv_SD RNN
author: Shanshan Wang, Gaurav Naithani, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a low algorithmic latency adaptation of the deep clustering approach to speaker-independent speech separation. It consists of three parts: a) the usage of long-short-term-memory (LSTM) networks instead of their bidirectional variant used in the original work, b) using a short synthesis window (here 8 ms) required for low-latency operation, and, c) using a buffer in the beginning of audio mixture to estimate cluster centres corresponding to constituent speakers which are then utilized to separate speakers within the rest of the signal. The buffer duration would serve as an initialization phase after which the system is capable of operating with 8 ms algorithmic latency. We evaluate our proposed approach on two-speaker mixtures from the Wall Street Journal (WSJ0) corpus. We observe that the use of LSTM yields around one dB lower SDR as compared to the baseline bidirectional LSTM in terms of source to distortion ratio (SDR). Moreover, using an 8 ms synthesis window instead of 32 ms degrades the separation performance by around 2.1 dB as compared to the baseline. Finally, we also report separation performance with different buffer durations noting that separation can be achieved even for buffer duration as low as 300ms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07033](http://arxiv.org/abs/1902.07033)

##### PDF
[http://arxiv.org/pdf/1902.07033](http://arxiv.org/pdf/1902.07033)

