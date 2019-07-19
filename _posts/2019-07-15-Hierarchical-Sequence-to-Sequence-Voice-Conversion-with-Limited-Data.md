---
layout: post
title: "Hierarchical Sequence to Sequence Voice Conversion with Limited Data"
date: 2019-07-15 07:54:46
categories: arXiv_SD
tags: arXiv_SD Attention Speech_Recognition NMT Recognition
author: Praveen Narayanan, Punarjay Chakravarty, Francois Charette, Gint Puskorius
mathjax: true
---

* content
{:toc}

##### Abstract
We present a voice conversion solution using recurrent sequence to sequence modeling for DNNs. Our solution takes advantage of recent advances in attention based modeling in the fields of Neural Machine Translation (NMT), Text-to-Speech (TTS) and Automatic Speech Recognition (ASR). The problem consists of converting between voices in a parallel setting when {\it $<$source,target$>$} audio pairs are available. Our seq2seq architecture makes use of a hierarchical encoder to summarize input audio frames. On the decoder side, we use an attention based architecture used in recent TTS works. Since there is a dearth of large multispeaker voice conversion databases needed for training DNNs, we resort to training the network with a large single speaker dataset as an autoencoder. This is then adapted for the smaller multispeaker voice conversion datasets available for voice conversion. In contrast with other voice conversion works that use $F_0$, duration and linguistic features, our system uses mel spectrograms as the audio representation. Output mel frames are converted back to audio using a wavenet vocoder.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1907.07769](https://arxiv.org/abs/1907.07769)

##### PDF
[https://arxiv.org/pdf/1907.07769](https://arxiv.org/pdf/1907.07769)

