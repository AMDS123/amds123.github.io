---
layout: post
title: "On Loss Functions for Supervised Monaural Time-Domain Speech Enhancement"
date: 2019-09-03 09:32:11
categories: arXiv_SD
tags: arXiv_SD Deep_Learning
author: Morten Kolb&#xe6;k, Zheng-Hua Tan, S&#xf8;ren Holdt Jensen, Jesper Jensen
mathjax: true
---

* content
{:toc}

##### Abstract
Many deep learning-based speech enhancement algorithms are designed to minimize the mean-square error (MSE) in some transform domain between a predicted and a target speech signal. However, optimizing for MSE does not necessarily guarantee high speech quality or intelligibility, which is the ultimate goal of many speech enhancement algorithms. Additionally, only little is known about the impact of the loss function on the emerging class of time-domain deep learning-based speech enhancement systems. We study how popular loss functions influence the performance of deep learning-based speech enhancement systems. First, we demonstrate that perceptually inspired loss functions might be advantageous if the receiver is the human auditory system. Furthermore, we show that the learning rate is a crucial design parameter even for adaptive gradient-based optimizers, which has been generally overlooked in the literature. Also, we found that waveform matching performance metrics must be used with caution as they in certain situations can fail completely. Finally, we show that a loss function based on scale-invariant signal-to-distortion ratio (SI-SDR) achieves good general performance across a range of popular speech enhancement evaluation metrics, which suggests that SI-SDR is a good candidate as a general-purpose loss function for speech enhancement systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01019](http://arxiv.org/abs/1909.01019)

##### PDF
[http://arxiv.org/pdf/1909.01019](http://arxiv.org/pdf/1909.01019)

