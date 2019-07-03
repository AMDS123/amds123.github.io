---
layout: post
title: "LSTM Language Models for LVCSR in First-Pass Decoding and Lattice-Rescoring"
date: 2019-07-01 19:29:04
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model
author: Eugen Beck, Wei Zhou, Ralf Schl&#xfc;ter, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
LSTM based language models are an important part of modern LVCSR systems as they significantly improve performance over traditional backoff language models. Incorporating them efficiently into decoding has been notoriously difficult. In this paper we present an approach based on a combination of one-pass decoding and lattice rescoring. We perform decoding with the LSTM-LM in the first pass but recombine hypothesis that share the last two words, afterwards we rescore the resulting lattice. We run our systems on GPGPU equipped machines and are able to produce competitive results on the Hub5'00 and Librispeech evaluation corpora with a runtime better than real-time. In addition we shortly investigate the possibility to carry out the full sum over all state-sequences belonging to a given word-hypothesis during decoding without recombination.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01030](http://arxiv.org/abs/1907.01030)

##### PDF
[http://arxiv.org/pdf/1907.01030](http://arxiv.org/pdf/1907.01030)

