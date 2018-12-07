---
layout: post
title: "On the Inductive Bias of Word-Character-Level Multi-Task Learning for Speech Recognition"
date: 2018-11-28 10:37:24
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Jan Kremer, Lasse Borgholt, Lars Maal&#xf8;e
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end automatic speech recognition (ASR) commonly transcribes audio signals into sequences of characters while its performance is evaluated by measuring the word-error rate (WER). This suggests that predicting sequences of words directly may be helpful instead. However, training with word-level supervision can be more difficult due to the sparsity of examples per label class. In this paper we analyze an end-to-end ASR model that combines a word-and-character representation in a multi-task learning (MTL) framework. We show that it improves on the WER and study how the word-level model can benefit from character-level supervision by analyzing the learned inductive preference bias of each model component empirically. We find that by adding character-level supervision, the MTL model interpolates between recognizing more frequent words (preferred by the word-level model) and shorter words (preferred by the character-level model).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02308](http://arxiv.org/abs/1812.02308)

##### PDF
[http://arxiv.org/pdf/1812.02308](http://arxiv.org/pdf/1812.02308)

