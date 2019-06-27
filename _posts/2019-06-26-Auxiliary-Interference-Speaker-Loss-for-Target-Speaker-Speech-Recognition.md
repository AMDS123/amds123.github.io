---
layout: post
title: "Auxiliary Interference Speaker Loss for Target-Speaker Speech Recognition"
date: 2019-06-26 07:09:57
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Naoyuki Kanda, Shota Horiguchi, Ryoichi Takashima, Yusuke Fujita, Kenji Nagamatsu, Shinji Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel auxiliary loss function for target-speaker automatic speech recognition (ASR). Our method automatically extracts and transcribes target speaker's utterances from a monaural mixture of multiple speakers speech given a short sample of the target speaker. The proposed auxiliary loss function attempts to additionally maximize interference speaker ASR accuracy during training. This will regularize the network to achieve a better representation for speaker separation, thus achieving better accuracy on the target-speaker ASR. We evaluated our proposed method using two-speaker-mixed speech in various signal-to-interference-ratio conditions. We first built a strong target-speaker ASR baseline based on the state-of-the-art lattice-free maximum mutual information. This baseline achieved a word error rate (WER) of 18.06% on the test set while a normal ASR trained with clean data produced a completely corrupted result (WER of 84.71%). Then, our proposed loss further reduced the WER by 6.6% relative to this strong baseline, achieving a WER of 16.87%. In addition to the accuracy improvement, we also showed that the auxiliary output branch for the proposed loss can even be used for a secondary ASR for interference speakers' speech.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10876](http://arxiv.org/abs/1906.10876)

##### PDF
[http://arxiv.org/pdf/1906.10876](http://arxiv.org/pdf/1906.10876)

