---
layout: post
title: "Trainable Time Warping: Aligning Time-Series in the Continuous-Time Domain"
date: 2019-03-21 21:42:19
categories: arXiv_AI
tags: arXiv_AI CNN Optimization Classification
author: Soheil Khorram, Melvin G McInnis, Emily Mower Provost
mathjax: true
---

* content
{:toc}

##### Abstract
DTW calculates the similarity or alignment between two signals, subject to temporal warping. However, its computational complexity grows exponentially with the number of time-series. Although there have been algorithms developed that are linear in the number of time-series, they are generally quadratic in time-series length. The exception is generalized time warping (GTW), which has linear computational cost. Yet, it can only identify simple time warping functions. There is a need for a new fast, high-quality multisequence alignment algorithm. We introduce trainable time warping (TTW), whose complexity is linear in both the number and the length of time-series. TTW performs alignment in the continuous-time domain using a sinc convolutional kernel and a gradient-based optimization technique. We compare TTW and GTW on 85 UCR datasets in time-series averaging and classification. TTW outperforms GTW on 67.1% of the datasets for the averaging tasks, and 61.2% of the datasets for the classification tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09245](http://arxiv.org/abs/1903.09245)

##### PDF
[http://arxiv.org/pdf/1903.09245](http://arxiv.org/pdf/1903.09245)

