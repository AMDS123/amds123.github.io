---
layout: post
title: "Evaluation of post-processing algorithms for polyphonic sound event detection"
date: 2019-06-17 09:13:13
categories: arXiv_SD
tags: arXiv_SD Segmentation Optimization Prediction Detection
author: Leo Cances, Patrice Guyot, Thomas Pellegrini
mathjax: true
---

* content
{:toc}

##### Abstract
Sound event detection (SED) aims at identifying audio events (audio tagging task) in recordings and then locating them temporally (localization task). This last task ends with the segmentation of the frame-level class predictions, that determines the onsets and offsets of the audio events. Yet, this step is often overlooked in scientific publications. In this paper, we focus on the post-processing algorithms used to identify the audio event boundaries. Different post-processing steps are investigated, through smoothing, thresholding, and optimization. In particular, we evaluate different approaches for temporal segmentation, namely statistic-based and parametric methods. Experiments are carried out on the DCASE 2018 challenge task 4 data. We compared post-processing algorithms on the temporal prediction curves of two models: one based on the challenge's baseline and a Multiple Instance Learning (MIL) model. Results show the crucial impact of the post-processing methods on the final detection score. Statistic-based methods yield a 22.9% event-based F-score on the evaluation set with our MIL model. Moreover, the best results were obtained using class-dependent parametric methods with 32.0% F-score.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06909](http://arxiv.org/abs/1906.06909)

##### PDF
[http://arxiv.org/pdf/1906.06909](http://arxiv.org/pdf/1906.06909)

