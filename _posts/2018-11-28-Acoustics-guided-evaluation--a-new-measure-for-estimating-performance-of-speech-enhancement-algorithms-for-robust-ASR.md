---
layout: post
title: "Acoustics-guided evaluation : a new measure for estimating performance of speech enhancement algorithms for robust ASR"
date: 2018-11-28 12:13:23
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Optimization Deep_Learning Language_Model Relation Recognition
author: Li Chai, Jun Du, Chin-Hui Lee
mathjax: true
---

* content
{:toc}

##### Abstract
One challenging problem of robust automatic speech recognition (ASR) is how to measure the goodness of a speech enhancement algorithm (SEA) without calculating the word error rate (WER) due to the high costs of manual transcriptions, language modeling and decoding process. Traditional measures like PESQ and STOI for evaluating the speech quality and intelligibility were verified to have relatively low correlations with WER. In this study, a novel acoustics-guided evaluation (AGE) measure is proposed for estimating performance of SEAs for robust ASR. AGE consists of three consecutive steps, namely the low-level representations via the feature extraction, high-level representations via the nonlinear mapping with the acoustic model (AM), and the final AGE calculation between the representations of clean speech and degraded speech. Specifically, state posterior probabilities from neural network based AM are adopted for the high-level representations and the cross-entropy criterion is used to calculate AGE. Experiments demonstrate AGE could yield consistently highest correlations with WER and give the most accurate estimation of ASR performance compared with PESQ, STOI, and acoustic confidence measure using Entropy. Potentially, AGE could be adopted to guide the parameter optimization of deep learning based SEAs to further improve the recognition performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11517](http://arxiv.org/abs/1811.11517)

##### PDF
[http://arxiv.org/pdf/1811.11517](http://arxiv.org/pdf/1811.11517)

