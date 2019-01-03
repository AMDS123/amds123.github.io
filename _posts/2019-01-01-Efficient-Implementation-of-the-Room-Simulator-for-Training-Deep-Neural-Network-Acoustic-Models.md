---
layout: post
title: "Efficient Implementation of the Room Simulator for Training Deep Neural Network Acoustic Models"
date: 2019-01-01 00:56:51
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Chanwoo Kim, Ehsan Variani, Arun Narayanan, Michiel Bacchiani
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe how to efficiently implement an acoustic room simulator to generate large-scale simulated data for training deep neural networks. Even though Google Room Simulator in [1] was shown to be quite effective in reducing the Word Error Rates (WERs) for far-field applications by generating simulated far-field training sets, it requires a very large number of Fast Fourier Transforms (FFTs) of large size. Room Simulator in [1] used approximately 80 percent of Central Processing Unit (CPU) usage in our CPU + Graphics Processing Unit (GPU) training architecture [2]. In this work, we implement an efficient OverLap Addition (OLA) based filtering using the open-source FFTW3 library. Further, we investigate the effects of the Room Impulse Response (RIR) lengths. Experimentally, we conclude that we can cut the tail portions of RIRs whose power is less than 20 dB below the maximum power without sacrificing the speech recognition accuracy. However, we observe that cutting RIR tail more than this threshold harms the speech recognition accuracy for rerecorded test sets. Using these approaches, we were able to reduce CPU usage for the room simulator portion down to 9.69 percent in CPU/GPU training architecture. Profiling result shows that we obtain 22.4 times speed-up on a single machine and 37.3 times speed up on Google's distributed training infrastructure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.03439](http://arxiv.org/abs/1712.03439)

##### PDF
[http://arxiv.org/pdf/1712.03439](http://arxiv.org/pdf/1712.03439)

