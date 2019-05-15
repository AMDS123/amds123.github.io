---
layout: post
title: "Imputing Missing Events in Continuous-Time Event Streams"
date: 2019-05-14 12:55:42
categories: arXiv_AI
tags: arXiv_AI RNN Prediction
author: Hongyuan Mei, Guanghui Qin, Jason Eisner
mathjax: true
---

* content
{:toc}

##### Abstract
Events in the world may be caused by other, unobserved events. We consider sequences of events in continuous time. Given a probability model of complete sequences, we propose particle smoothing---a form of sequential importance sampling---to impute the missing events in an incomplete sequence. We develop a trainable family of proposal distributions based on a type of bidirectional continuous-time LSTM: Bidirectionality lets the proposals condition on future observations, not just on the past as in particle filtering. Our method can sample an ensemble of possible complete sequences (particles), from which we form a single consensus prediction that has low Bayes risk under our chosen loss metric. We experiment in multiple synthetic and real domains, using different missingness mechanisms, and modeling the complete sequences in each domain with a neural Hawkes process (Mei & Eisner 2017). On held-out incomplete sequences, our method is effective at inferring the ground-truth unobserved events, with particle smoothing consistently improving upon particle filtering.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05570](https://arxiv.org/abs/1905.05570)

##### PDF
[https://arxiv.org/pdf/1905.05570](https://arxiv.org/pdf/1905.05570)

