---
layout: post
title: "A spelling correction model for end-to-end speech recognition"
date: 2019-02-19 18:18:59
categories: arXiv_AI
tags: arXiv_AI Attention Speech_Recognition Language_Model Recognition
author: Jinxi Guo, Tara N. Sainath, Ron J. Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based sequence-to-sequence models for speech recognition jointly train an acoustic model, language model (LM), and alignment mechanism using a single neural network and require only parallel audio-text pairs. Thus, the language model component of the end-to-end model is only trained on transcribed audio-text pairs, which leads to performance degradation especially on rare words. While there have been a variety of work that look at incorporating an external LM trained on text-only data into the end-to-end framework, none of them have taken into account the characteristic error distribution made by the model. In this paper, we propose a novel approach to utilizing text-only data, by training a spelling correction (SC) model to explicitly correct those errors. On the LibriSpeech dataset, we demonstrate that the proposed model results in an 18.6% relative improvement in WER over the baseline model when directly correcting top ASR hypothesis, and a 29.0% relative improvement when further rescoring an expanded n-best list using an external LM.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07178](http://arxiv.org/abs/1902.07178)

##### PDF
[http://arxiv.org/pdf/1902.07178](http://arxiv.org/pdf/1902.07178)

