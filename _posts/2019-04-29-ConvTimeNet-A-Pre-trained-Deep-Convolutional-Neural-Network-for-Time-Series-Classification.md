---
layout: post
title: "ConvTimeNet: A Pre-trained Deep Convolutional Neural Network for Time Series Classification"
date: 2019-04-29 10:12:17
categories: arXiv_AI
tags: arXiv_AI CNN Classification
author: Kathan Kashiparekh, Jyoti Narwariya, Pankaj Malhotra, Lovekesh Vig, Gautam Shroff
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep neural networks often requires careful hyper-parameter tuning and significant computational resources. In this paper, we propose ConvTimeNet (CTN): an off-the-shelf deep convolutional neural network (CNN) trained on diverse univariate time series classification (TSC) source tasks. Once trained, CTN can be easily adapted to new TSC target tasks via a small amount of fine-tuning using labeled instances from the target tasks. We note that the length of convolutional filters is a key aspect when building a pre-trained model that can generalize to time series of different lengths across datasets. To achieve this, we incorporate filters of multiple lengths in all convolutional layers of CTN to capture temporal features at multiple time scales. We consider all 65 datasets with time series of lengths up to 512 points from the UCR TSC Benchmark for training and testing transferability of CTN: We train CTN on a randomly chosen subset of 24 datasets using a multi-head approach with a different softmax layer for each training dataset, and study generalizability and transferability of the learned filters on the remaining 41 TSC datasets. We observe significant gains in classification accuracy as well as computational efficiency when using pre-trained CTN as a starting point for subsequent task-specific fine-tuning compared to existing state-of-the-art TSC approaches. We also provide qualitative insights into the working of CTN by: i) analyzing the activations and filters of first convolution layer suggesting the filters in CTN are generically useful, ii) analyzing the impact of the design decision to incorporate multiple length decisions, and iii) finding regions of time series that affect the final classification decision via occlusion sensitivity analysis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12546](http://arxiv.org/abs/1904.12546)

##### PDF
[http://arxiv.org/pdf/1904.12546](http://arxiv.org/pdf/1904.12546)

