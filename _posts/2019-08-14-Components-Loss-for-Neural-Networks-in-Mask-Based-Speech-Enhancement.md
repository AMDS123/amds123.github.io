---
layout: post
title: "Components Loss for Neural Networks in Mask-Based Speech Enhancement"
date: 2019-08-14 12:03:27
categories: arXiv_SD
tags: arXiv_SD CNN Deep_Learning
author: Ziyi Xu, Samy Elshamy, Ziyue Zhao, Tim Fingscheidt
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating time-frequency domain masks for single-channel speech enhancement using deep learning methods has recently become a popular research field with promising results. In this paper, we propose a novel components loss (CL) for the training of neural networks for mask-based speech enhancement. During the training process, the proposed CL offers separate control over preservation of the speech component quality, suppression of the residual noise component, and preservation of a naturally sounding residual noise component. We illustrate the potential of the proposed CL by evaluating a standard convolutional neural network (CNN) for mask-based speech enhancement. The new CL obtains a better and more balanced performance in almost all employed instrumental quality metrics over the baseline losses, the latter comprising the conventional mean squared error (MSE) loss and also auditory-related loss functions, such as the perceptual evaluation of speech quality (PESQ) loss and the recently proposed perceptual weighting filter loss. Particularly, applying the CL offers better speech component quality, better overall enhanced speech perceptual quality, as well as a more naturally sounding residual noise. On average, an at least 0.1 points higher PESQ score on the enhanced speech is obtained while also obtaining a higher SNR improvement by more than 0.5 dB, for seen noise types. This improvement is stronger for unseen noise types, where an about 0.2 points higher PESQ score on the enhanced speech is obtained, while also the output SNR is ahead by more than 0.5 dB. The new proposed CL is easy to implement and code is provided at https://github.com/ifnspaml/Components-Loss.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05087](http://arxiv.org/abs/1908.05087)

##### PDF
[http://arxiv.org/pdf/1908.05087](http://arxiv.org/pdf/1908.05087)

