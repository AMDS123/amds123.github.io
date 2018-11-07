---
layout: post
title: "FloWaveNet : A Generative Flow for Raw Audio"
date: 2018-11-06 04:30:41
categories: arXiv_SD
tags: arXiv_SD
author: Sungwon Kim, Sang-gil Lee, Jongyoon Song, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
Most of modern text-to-speech architectures use a WaveNet vocoder for synthesizing a high-fidelity waveform audio, but there has been a limitation for practical applications due to its slow autoregressive sampling scheme. A recently suggested Parallel WaveNet has achieved a real-time audio synthesis by incorporating Inverse Autogressive Flow (IAF) for parallel sampling. However, the Parallel WaveNet requires a two-stage training pipeline with a well-trained teacher network and is prone to mode collapsing if using a probability distillation training only. We propose FloWaveNet, a flow-based generative model for raw audio synthesis. FloWaveNet requires only a single maximum likelihood loss without any additional auxiliary terms and is inherently parallel due to the flow-based transformation. The model can efficiently sample the raw audio in real-time with a clarity comparable to the original WaveNet and ClariNet. Codes and samples for all models including our FloWaveNet is available via GitHub: https://github.com/ksw0306/FloWaveNet

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02155](http://arxiv.org/abs/1811.02155)

##### PDF
[http://arxiv.org/pdf/1811.02155](http://arxiv.org/pdf/1811.02155)

