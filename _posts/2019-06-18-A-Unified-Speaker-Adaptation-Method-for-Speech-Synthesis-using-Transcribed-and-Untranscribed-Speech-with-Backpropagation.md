---
layout: post
title: "A Unified Speaker Adaptation Method for Speech Synthesis using Transcribed and Untranscribed Speech with Backpropagation"
date: 2019-06-18 07:24:45
categories: arXiv_CL
tags: arXiv_CL
author: Hieu-Thi Luong, Junichi Yamagishi
mathjax: true
---

* content
{:toc}

##### Abstract
By representing speaker characteristic as a single fixed-length vector extracted solely from speech, we can train a neural multi-speaker speech synthesis model by conditioning the model on those vectors. This model can also be adapted to unseen speakers regardless of whether the transcript of adaptation data is available or not. However, this setup restricts the speaker component to just a single bias vector, which in turn limits the performance of adaptation process. In this study, we propose a novel speech synthesis model, which can be adapted to unseen speakers by fine-tuning part of or all of the network using either transcribed or untranscribed speech. Our methodology essentially consists of two steps: first, we split the conventional acoustic model into a speaker-independent (SI) linguistic encoder and a speaker-adaptive (SA) acoustic decoder; second, we train an auxiliary acoustic encoder that can be used as a substitute for the linguistic encoder whenever linguistic features are unobtainable. The results of objective and subjective evaluations show that adaptation using either transcribed or untranscribed speech with our methodology achieved a reasonable level of performance with an extremely limited amount of data and greatly improved performance with more data. Surprisingly, adaptation with untranscribed speech surpassed the transcribed counterpart in the subjective test, which reveals the limitations of the conventional acoustic model and hints at potential directions for improvements.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07414](http://arxiv.org/abs/1906.07414)

##### PDF
[http://arxiv.org/pdf/1906.07414](http://arxiv.org/pdf/1906.07414)

