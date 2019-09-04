---
layout: post
title: "Demucs: Deep Extractor for Music Sources with extra unlabeled data remixed"
date: 2019-09-03 13:41:56
categories: arXiv_SD
tags: arXiv_SD Weakly_Supervised CNN Deep_Learning
author: Alexandre Défossez (SIERRA, PSL, FAIR), Nicolas Usunier (FAIR), Léon Bottou (FAIR), Francis Bach (PSL, DI-ENS, SIERRA)
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of source separation for music using deep learning with four known sources: drums, bass, vocals and other accompaniments. State-of-the-art approaches predict soft masks over mixture spectrograms while methods working on the waveform are lagging behind as measured on the standard MusDB benchmark. Our contribution is two fold. (i) We introduce a simple convolutional and recurrent model that outperforms the state-of-the-art model on waveforms, that is, Wave-U-Net, by 1.6 points of SDR (signal to distortion ratio). (ii) We propose a new scheme to leverage unlabeled music. We train a first model to extract parts with at least one source silent in unlabeled tracks, for instance without bass. We remix this extract with a bass line taken from the supervised dataset to form a new weakly supervised training example. Combining our architecture and scheme, we show that waveform methods can play in the same ballpark as spectrogram ones.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01174](https://arxiv.org/abs/1909.01174)

##### PDF
[https://arxiv.org/pdf/1909.01174](https://arxiv.org/pdf/1909.01174)

