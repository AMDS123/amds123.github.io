---
layout: post
title: "TimbreTron: A WaveNet)) Pipeline for Musical Timbre Transfer"
date: 2019-05-02 02:40:24
categories: arXiv_SD
tags: arXiv_SD Style_Transfer CNN
author: Sicong Huang, Qiyang Li, Cem Anil, Xuchan Bao, Sageev Oore, Roger B. Grosse
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we address the problem of musical timbre transfer, where the goal is to manipulate the timbre of a sound sample from one instrument to match another instrument while preserving other musical content, such as pitch, rhythm, and loudness. In principle, one could apply image-based style transfer techniques to a time-frequency representation of an audio signal, but this depends on having a representation that allows independent manipulation of timbre as well as high-quality waveform generation. We introduce TimbreTron, a method for musical timbre transfer which applies "image" domain style transfer to a time-frequency representation of the audio signal, and then produces a high-quality waveform using a conditional WaveNet synthesizer. We show that the Constant Q Transform (CQT) representation is particularly well-suited to convolutional architectures due to its approximate pitch equivariance. Based on human perceptual evaluations, we confirmed that TimbreTron recognizably transferred the timbre while otherwise preserving the musical content, for both monophonic and polyphonic samples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09620](http://arxiv.org/abs/1811.09620)

##### PDF
[http://arxiv.org/pdf/1811.09620](http://arxiv.org/pdf/1811.09620)

