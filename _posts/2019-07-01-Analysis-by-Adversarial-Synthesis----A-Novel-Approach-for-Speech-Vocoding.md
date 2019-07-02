---
layout: post
title: "Analysis by Adversarial Synthesis -- A Novel Approach for Speech Vocoding"
date: 2019-07-01 13:46:54
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN RNN
author: Ahmed Mustafa, Arijit Biswas, Christian Bergler, Julia Schottenhamml, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Classical parametric speech coding techniques provide a compact representation for speech signals. This affords a very low transmission rate but with a reduced perceptual quality of the reconstructed signals. Recently, autoregressive deep generative models such as WaveNet and SampleRNN have been used as speech vocoders to scale up the perceptual quality of the reconstructed signals without increasing the coding rate. However, such models suffer from a very slow signal generation mechanism due to their sample-by-sample modelling approach. In this work, we introduce a new methodology for neural speech vocoding based on generative adversarial networks (GANs). A fake speech signal is generated from a very compressed representation of the glottal excitation using conditional GANs as a deep generative model. This fake speech is then refined using the LPC parameters of the original speech signal to obtain a natural reconstruction. The reconstructed speech waveforms based on this approach show a higher perceptual quality than the classical vocoder counterparts according to subjective and objective evaluation scores for a dataset of 30 male and female speakers. Moreover, the usage of GANs enables to generate signals in one-shot compared to autoregressive generative models. This makes GANs promising for exploration to implement high-quality neural vocoders.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00772](http://arxiv.org/abs/1907.00772)

##### PDF
[http://arxiv.org/pdf/1907.00772](http://arxiv.org/pdf/1907.00772)

