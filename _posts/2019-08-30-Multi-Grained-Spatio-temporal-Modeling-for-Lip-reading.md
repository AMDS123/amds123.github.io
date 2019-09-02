---
layout: post
title: "Multi-Grained Spatio-temporal Modeling for Lip-reading"
date: 2019-08-30 09:50:20
categories: arXiv_CV
tags: arXiv_CV Attention RNN
author: Chenhao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Lip-reading aims to recognize speech content from videos via visual analysis of speakers' lip movements. This is a challenging task due to the existence of homophemes-words which involve identical or highly similar lip movements, as well as diverse lip appearances and motion patterns among the speakers. To address these challenges, we propose a novel lip-reading model which captures not only the nuance between words but also styles of different speakers, by a multi-grained spatio-temporal modeling of the speaking process. Specifically, we first extract both frame-level fine-grained features and short-term medium-grained features by the visual front-end, which are then combined to obtain discriminative representations for words with similar phonemes. Next, a bidirectional ConvLSTM augmented with temporal attention aggregates spatio-temporal information in the entire input sequence, which is expected to be able to capture the coarse-gained patterns of each word and robust to various conditions in speaker identity, lighting conditions, and so on. By making full use of the information from different levels in a unified framework, the model is not only able to distinguish words with similar pronunciations, but also becomes robust to appearance changes. We evaluate our method on two challenging word-level lip-reading benchmarks and show the effectiveness of the proposed method, which also demonstrate the above claims.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11618](http://arxiv.org/abs/1908.11618)

##### PDF
[http://arxiv.org/pdf/1908.11618](http://arxiv.org/pdf/1908.11618)

