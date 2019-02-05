---
layout: post
title: "Real-Time Steganalysis for Stream Media Based on Multi-channel Convolutional Sliding Windows"
date: 2019-02-04 16:23:56
categories: arXiv_AI
tags: arXiv_AI GAN Face Embedding CNN Detection Relation
author: Zhongliang Yang, Hao Yang, Yuting Hu, Yongfeng Huang, Yu-Jin Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Previous VoIP steganalysis methods face great challenges in detecting speech signals at low embedding rates, and they are also generally difficult to perform real-time detection, making them hard to truly maintain cyberspace security. To solve these two challenges, in this paper, combined with the sliding window detection algorithm and Convolution Neural Network we propose a real-time VoIP steganalysis method which based on multi-channel convolution sliding windows. In order to analyze the correlations between frames and different neighborhood frames in a VoIP signal, we define multi channel sliding detection windows. Within each sliding window, we design two feature extraction channels which contain multiple convolution layers with multiple convolution kernels each layer to extract correlation features of the input signal. Then based on these extracted features, we use a forward fully connected network for feature fusion. Finally, by analyzing the statistical distribution of these features, the discriminator will determine whether the input speech signal contains covert information or not.We designed several experiments to test the proposed model's detection ability under various conditions, including different embedding rates, different speech length, etc. Experimental results showed that the proposed model outperforms all the previous methods, especially in the case of low embedding rate, which showed state-of-the-art performance. In addition, we also tested the detection efficiency of the proposed model, and the results showed that it can achieve almost real-time detection of VoIP speech signals.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01286](http://arxiv.org/abs/1902.01286)

##### PDF
[http://arxiv.org/pdf/1902.01286](http://arxiv.org/pdf/1902.01286)

