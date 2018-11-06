---
layout: post
title: "Cycle-consistency training for end-to-end speech recognition"
date: 2018-11-02 06:32:58
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Language_Model Recognition
author: Takaaki Hori, Ramon Astudillo, Tomoki Hayashi, Yu Zhang, Shinji Watanabe, Jonathan Le Roux
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method to train end-to-end automatic speech recognition (ASR) models using unpaired data. Although the end-to-end approach can eliminate the need for expert knowledge such as pronunciation dictionaries to build ASR systems, it still requires a large amount of paired data, i.e., speech utterances and their transcriptions. Cycle-consistency losses have been recently proposed as a way to mitigate the problem of limited paired data. These approaches compose a reverse operation with a given transformation, e.g., text-to-speech (TTS) with ASR, to build a loss that only requires unsupervised data, speech in this example. Applying cycle consistency to ASR models is not trivial since fundamental information, such as speaker traits, are lost in the intermediate text bottleneck. To solve this problem, this work presents a loss that is based on the speech encoder state sequence instead of the raw speech signal. This is achieved by training a Text-To-Encoder model and defining a loss based on the encoder reconstruction error. Experimental results on the LibriSpeech corpus show that the proposed cycle-consistency training reduced the word error rate by 14.7% from an initial model trained with 100-hour paired data, using an additional 360 hours of audio data without transcriptions. We also investigate the use of text-only data mainly for language modeling to further improve the performance in the unpaired data training scenario.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01690](http://arxiv.org/abs/1811.01690)

##### PDF
[http://arxiv.org/pdf/1811.01690](http://arxiv.org/pdf/1811.01690)

