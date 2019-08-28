---
layout: post
title: "Neural Harmonic-plus-Noise Waveform Model with Trainable Maximum Voice Frequency for Text-to-Speech Synthesis"
date: 2019-08-27 15:01:29
categories: arXiv_SD
tags: arXiv_SD
author: Xin Wang, Junichi Yamagishi
mathjax: true
---

* content
{:toc}

##### Abstract
Neural source-filter (NSF) models are deep neural networks that produce waveforms given input acoustic features. They use dilated-convolution-based neural filter modules to filter sine-based excitation for waveform generation, which is different from WaveNet and flow-based models. One of the NSF models, called harmonic-plus-noise NSF (h-NSF) model, uses separate pairs of source and neural filters to generate harmonic and noise waveform components. It is close to WaveNet in terms of speech quality while being superior in generation speed. 
 The h-NSF model can be improved even further. While h-NSF merges the harmonic and noise components using pre-defined digital low- and high-pass filters, it is well known that the maximum voice frequency (MVF) that separates the periodic and aperiodic spectral bands are time-variant. Therefore, we propose a new h-NSF model with time-variant and trainable MVF. We parameterize the digital low- and high-pass filters as windowed-sinc filters and predict their cut-off frequency (i.e., MVF) from the input acoustic features. Our experiments demonstrated that the new model can predict a good trajectory of the MVF and produce high-quality speech for a text-to-speech synthesis system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10256](http://arxiv.org/abs/1908.10256)

##### PDF
[http://arxiv.org/pdf/1908.10256](http://arxiv.org/pdf/1908.10256)

