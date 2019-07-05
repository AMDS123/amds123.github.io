---
layout: post
title: "Ensemble Models for Spoofing Detection in Automatic Speaker Verification"
date: 2019-07-04 08:32:53
categories: arXiv_SD
tags: arXiv_SD Detection
author: Bhusan Chettri, Daniel Stoller, Veronica Morfi, Marco A. Mart&#xed;nez Ram&#xed;rez, Emmanouil Benetos, Bob L. Sturm
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting spoofing attempts of automatic speaker verification (ASV) systems is challenging, especially when using only one modeling approach. For robustness, we use both deep neural networks and traditional machine learning models and combine them as ensemble models through logistic regression. They are trained to detect logical access (LA) and physical access (PA) attacks on the dataset released as part of the ASV Spoofing and Countermeasures Challenge 2019. We propose dataset partitions that ensure different attack types are present during training and validation to improve system robustness. Our ensemble model outperforms all our single models and the baselines from the challenge for both attack types. We investigate why some models on the PA dataset strongly outperform others and find that spoofed recordings in the dataset tend to have longer silences at the end than genuine ones. By removing them, the PA task becomes much more challenging, with the tandem detection cost function (t-DCF) of our best single model rising from 0.1672 to 0.5018 and equal error rate (EER) increasing from 5.98% to 19.8% on the development set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04589](http://arxiv.org/abs/1904.04589)

##### PDF
[http://arxiv.org/pdf/1904.04589](http://arxiv.org/pdf/1904.04589)

