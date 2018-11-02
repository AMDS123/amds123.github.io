---
layout: post
title: "Designing an Effective Metric Learning Pipeline for Speaker Diarization"
date: 2018-11-01 01:51:17
categories: arXiv_SD
tags: arXiv_SD Knowledge Attention RNN Recommendation
author: Vivek Sivaraman Narayanaswamy, Jayaraman J. Thiagarajan, Huan Song, Andreas Spanias
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art speaker diarization systems utilize knowledge from external data, in the form of a pre-trained distance metric, to effectively determine relative speaker identities to unseen data. However, much of recent focus has been on choosing the appropriate feature extractor, ranging from pre-trained $i-$vectors to representations learned via different sequence modeling architectures (e.g. 1D-CNNs, LSTMs, attention models), while adopting off-the-shelf metric learning solutions. In this paper, we argue that, regardless of the feature extractor, it is crucial to carefully design a metric learning pipeline, namely the loss function, the sampling strategy and the discrimnative margin parameter, for building robust diarization systems. Furthermore, we propose to adopt a fine-grained validation process to obtain a comprehensive evaluation of the generalization power of metric learning pipelines. To this end, we measure diarization performance across different language speakers, and variations in the number of speakers in a recording. Using empirical studies, we provide interesting insights into the effectiveness of different design choices and make recommendations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00183](http://arxiv.org/abs/1811.00183)

##### PDF
[http://arxiv.org/pdf/1811.00183](http://arxiv.org/pdf/1811.00183)

