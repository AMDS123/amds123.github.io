---
layout: post
title: "Language Modelling for Sound Event Detection with Teacher Forcing and Scheduled Sampling"
date: 2019-07-19 13:26:03
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model Prediction Detection
author: Konstantinos Drossos, Shayan Gharib, Paul Magron, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
A sound event detection (SED) method typically takes as an input a sequence of audio frames and predicts the activities of sound events in each frame. In real-life recordings, the sound events exhibit some temporal structure: for instance, a "car horn" will likely be followed by a "car passing by". While this temporal structure is widely exploited in sequence prediction tasks (e.g., in machine translation), where language models (LM) are exploited, it is not satisfactorily modeled in SED. In this work we propose a method which allows a recurrent neural network (RNN) to learn an LM for the SED task. The method conditions the input of the RNN with the activities of classes at the previous time step. We evaluate our method using F1 score and error rate (ER) over three different and publicly available datasets; the TUT-SED Synthetic 2016 and the TUT Sound Events 2016 and 2017 datasets. The obtained results show an increase of 6% and 3% at the F1 (higher is better) and a decrease of 3% and 2% at ER (lower is better) for the TUT Sound Events 2016 and 2017 datasets, respectively, when using our method. On the contrary, with our method there is a decrease of 10% at F1 score and an increase of 11% at ER for the TUT-SED Synthetic 2016 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08506](http://arxiv.org/abs/1907.08506)

##### PDF
[http://arxiv.org/pdf/1907.08506](http://arxiv.org/pdf/1907.08506)

