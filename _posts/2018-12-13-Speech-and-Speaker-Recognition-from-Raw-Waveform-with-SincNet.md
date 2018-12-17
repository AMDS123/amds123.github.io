---
layout: post
title: "Speech and Speaker Recognition from Raw Waveform with SincNet"
date: 2018-12-13 16:01:11
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Recognition
author: Mirco Ravanelli, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks can learn complex and abstract representations, that are progressively obtained by combining simpler ones. A recent trend in speech and speaker recognition consists in discovering these representations starting from raw audio samples directly. Differently from standard hand-crafted features such as MFCCs or FBANK, the raw waveform can potentially help neural networks discover better and more customized representations. The high-dimensional raw inputs, however, can make training significantly more challenging. This paper summarizes our recent efforts to develop a neural architecture that efficiently processes speech from audio waveforms. In particular, we propose SincNet, a novel Convolutional Neural Network (CNN) that encourages the first layer to discover meaningful filters by exploiting parametrized sinc functions. In contrast to standard CNNs, which learn all the elements of each filter, only low and high cutoff frequencies of band-pass filters are directly learned from data. This inductive bias offers a very compact way to derive a customized front-end, that only depends on some parameters with a clear physical meaning. Our experiments, conducted on both speaker and speech recognition, show that the proposed architecture converges faster, performs better, and is more computationally efficient than standard CNNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05920](http://arxiv.org/abs/1812.05920)

##### PDF
[http://arxiv.org/pdf/1812.05920](http://arxiv.org/pdf/1812.05920)

