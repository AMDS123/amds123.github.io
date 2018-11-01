---
layout: post
title: "A Streamlined Encoder/Decoder Architecture for Melody Extraction"
date: 2018-10-30 18:15:03
categories: arXiv_SD
tags: arXiv_SD Segmentation CNN
author: Tsung-Han Hsieh, Li Su, Yi-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Melody extraction in polyphonic musical audio is important for music signal processing. In this paper, we propose a novel streamlined encoder/decoder network that is designed for the task. We make two technical contributions. First, drawing inspiration from a state-of-the-art model for semantic pixel-wise segmentation, we pass through the pooling indices between pooling and un-pooling layers to localize the melody in frequency. We can achieve result close to the state-of-the-art with much fewer convolutional layers and simpler convolution modules. Second, we propose a way to use the bottleneck layer of the network to estimate the existence of a melody line for each time frame, and make it possible to use a simple argmax function instead of ad-hoc thresholding to get the final estimation of the melody line. Our experiments on both vocal melody extraction and general melody extraction validate the effectiveness of the proposed model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12947](http://arxiv.org/abs/1810.12947)

##### PDF
[http://arxiv.org/pdf/1810.12947](http://arxiv.org/pdf/1810.12947)

