---
layout: post
title: "Seeing in the dark with recurrent convolutional neural networks"
date: 2018-11-21 01:05:48
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Till S. Hartmann
mathjax: true
---

* content
{:toc}

##### Abstract
Classical convolutional neural networks (cCNNs) are very good at categorizing objects in images. But, unlike human vision which is relatively robust to noise in images, the performance of cCNNs declines quickly as image quality worsens. Here we propose to use recurrent connections within the convolutional layers to make networks robust against pixel noise such as could arise from imaging at low light levels, and thereby significantly increase their performance when tested with simulated noisy video sequences. We show that cCNNs classify images with high signal to noise ratios (SNRs) well, but are easily outperformed when tested with low SNR images (high noise levels) by convolutional neural networks that have recurrency added to convolutional layers, henceforth referred to as gruCNNs. Addition of Bayes-optimal temporal integration to allow the cCNN to integrate multiple image frames still does not match gruCNN performance. Additionally, we show that at low SNRs, the probabilities predicted by the gruCNN (after calibration) have higher confidence than those predicted by the cCNN. We propose to consider recurrent connections in the early stages of neural networks as a solution to computer vision under imperfect lighting conditions and noisy environments; challenges faced during real-time video streams of autonomous driving at night, during rain or snow, and other non-ideal situations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08537](http://arxiv.org/abs/1811.08537)

##### PDF
[http://arxiv.org/pdf/1811.08537](http://arxiv.org/pdf/1811.08537)

