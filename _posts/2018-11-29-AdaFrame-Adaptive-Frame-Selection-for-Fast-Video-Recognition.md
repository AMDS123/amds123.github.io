---
layout: post
title: "AdaFrame: Adaptive Frame Selection for Fast Video Recognition"
date: 2018-11-29 19:08:52
categories: arXiv_CV
tags: arXiv_CV Inference Classification Prediction Recognition
author: Zuxuan Wu, Caiming Xiong, Chih-Yao Ma, Richard Socher, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We present AdaFrame, a framework that adaptively selects relevant frames on a per-input basis for fast video recognition. AdaFrame contains a Long Short-Term Memory network augmented with a global memory that provides context information for searching which frames to use over time. Trained with policy gradient methods, AdaFrame generates a prediction, determines which frame to observe next, and computes the utility, i.e., expected future rewards, of seeing more frames at each time step. At testing time, AdaFrame exploits predicted utilities to achieve adaptive lookahead inference such that the overall computational costs are reduced without incurring a decrease in accuracy. Extensive experiments are conducted on two large-scale video benchmarks, FCVID and AvtivityNet. AdaFrame matches the performance of using all frames with only 8.21 and 8.65 frames on FCVID and AvtivityNet, respectively. We further qualitatively demonstrate learned frame usage can indicate the difficulty of making classification decisions; easier samples need fewer frames while harder ones require more, both at instance-level within the same class and at class-level among different categories.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12432](http://arxiv.org/abs/1811.12432)

##### PDF
[http://arxiv.org/pdf/1811.12432](http://arxiv.org/pdf/1811.12432)

