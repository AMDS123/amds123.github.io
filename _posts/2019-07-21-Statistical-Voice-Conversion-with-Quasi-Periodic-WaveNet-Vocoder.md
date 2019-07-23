---
layout: post
title: "Statistical Voice Conversion with Quasi-Periodic WaveNet Vocoder"
date: 2019-07-21 09:29:46
categories: arXiv_SD
tags: arXiv_SD
author: Yi-Chiao Wu, Patrick Lumban Tobing, Tomoki Hayashi, Kazuhiro Kobayashi, Tomoki Toda
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate the effectiveness of a quasi-periodic WaveNet (QPNet) vocoder combined with a statistical spectral conversion technique for a voice conversion task. The WaveNet (WN) vocoder has been applied as the waveform generation module in many different voice conversion frameworks and achieves significant improvement over conventional vocoders. However, because of the fixed dilated convolution and generic network architecture, the WN vocoder lacks robustness against unseen input features and often requires a huge network size to achieve acceptable speech quality. Such limitations usually lead to performance degradation in the voice conversion task. To overcome this problem, the QPNet vocoder is applied, which includes a pitch-dependent dilated convolution component to enhance the pitch controllability and attain a more compact network than the WN vocoder. In the proposed method, input spectral features are first converted using a framewise deep neural network, and then the QPNet vocoder generates converted speech conditioned on the linearly converted prosodic and transformed spectral features. The experimental results confirm that the QPNet vocoder achieves significantly better performance than the same-size WN vocoder while maintaining comparable speech quality to the double-size WN vocoder. Index Terms: WaveNet, vocoder, voice conversion, pitch-dependent dilated convolution, pitch controllability

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08940](http://arxiv.org/abs/1907.08940)

##### PDF
[http://arxiv.org/pdf/1907.08940](http://arxiv.org/pdf/1907.08940)

