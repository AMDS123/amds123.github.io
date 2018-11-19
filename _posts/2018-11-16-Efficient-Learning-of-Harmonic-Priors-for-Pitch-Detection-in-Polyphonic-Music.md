---
layout: post
title: "Efficient Learning of Harmonic Priors for Pitch Detection in Polyphonic Music"
date: 2018-11-16 16:58:37
categories: arXiv_SD
tags: arXiv_SD Inference Detection Relation
author: Pablo A. Alvarado, Dan Stowell
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic music transcription (AMT) aims to infer a latent symbolic representation of a piece of music (piano-roll), given a corresponding observed audio recording. Transcribing polyphonic music (when multiple notes are played simultaneously) is a challenging problem, due to highly structured overlapping between harmonics. We study whether the introduction of physically inspired Gaussian process (GP) priors into audio content analysis models improves the extraction of patterns required for AMT. Audio signals are described as a linear combination of sources. Each source is decomposed into the product of an amplitude-envelope, and a quasi-periodic component process. We introduce the Mat\'ern spectral mixture (MSM) kernel for describing frequency content of singles notes. We consider two different regression approaches. In the sigmoid model every pitch-activation is independently non-linear transformed. In the softmax model several activation GPs are jointly non-linearly transformed. This introduce cross-correlation between activations. We use variational Bayes for approximate inference. We empirically evaluate how these models work in practice transcribing polyphonic music. We demonstrate that rather than encourage dependency between activations, what is relevant for improving pitch detection is to learnt priors that fit the frequency content of the sound events to detect.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.07104](http://arxiv.org/abs/1705.07104)

##### PDF
[http://arxiv.org/pdf/1705.07104](http://arxiv.org/pdf/1705.07104)

