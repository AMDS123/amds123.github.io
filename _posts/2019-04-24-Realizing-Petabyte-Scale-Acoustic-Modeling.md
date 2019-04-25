---
layout: post
title: "Realizing Petabyte Scale Acoustic Modeling"
date: 2019-04-24 00:39:25
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Sree Hari Krishnan Parthasarathi, Nitin Sivakrishnan, Pranav Ladkat, Nikko Strom
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale machine learning (ML) systems such as the Alexa automatic speech recognition (ASR) system continue to improve with increasing amounts of manually transcribed training data. Instead of scaling manual transcription to impractical levels, we utilize semi-supervised learning (SSL) to learn acoustic models (AM) from the vast firehose of untranscribed audio data. Learning an AM from 1 Million hours of audio presents unique ML and system design challenges. We present the design and evaluation of a highly scalable and resource efficient SSL system for AM. Employing the student/teacher learning paradigm, we focus on the student learning subsystem: a scalable and robust data pipeline that generates features and targets from raw audio, and an efficient model pipeline, including the distributed trainer, that builds a student model. Our evaluations show that, even without extensive hyper-parameter tuning, we obtain relative accuracy improvements in the 10 to 20$\%$ range, with higher gains in noisier conditions. The end-to-end processing time of this SSL system was 12 days, and several components in this system can trivially scale linearly with more compute resources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10584](http://arxiv.org/abs/1904.10584)

##### PDF
[http://arxiv.org/pdf/1904.10584](http://arxiv.org/pdf/1904.10584)

