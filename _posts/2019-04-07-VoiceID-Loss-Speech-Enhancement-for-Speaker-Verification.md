---
layout: post
title: "VoiceID Loss: Speech Enhancement for Speaker Verification"
date: 2019-04-07 08:07:20
categories: arXiv_SD
tags: arXiv_SD
author: Suwon Shon, Hao Tang, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose VoiceID loss, a novel loss function for training a speech enhancement model to improve the robustness of speaker verification. In contrast to the commonly used loss functions for speech enhancement such as the L2 loss, the VoiceID loss is based on the feedback from a speaker verification model to generate a ratio mask. The generated ratio mask is multiplied pointwise with the original spectrogram to filter out unnecessary components for speaker verification. In the experiments, we observed that the enhancement network, after training with the VoiceID loss, is able to ignore a substantial amount of time-frequency bins, such as those dominated by noise, for verification. The resulting model consistently improves the speaker verification system on both clean and noisy conditions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03601](http://arxiv.org/abs/1904.03601)

##### PDF
[http://arxiv.org/pdf/1904.03601](http://arxiv.org/pdf/1904.03601)

