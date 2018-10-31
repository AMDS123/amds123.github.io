---
layout: post
title: "Feature Map Filtering: Improving Visual Place Recognition with Convolutional Calibration"
date: 2018-10-30 00:33:51
categories: arXiv_RO
tags: arXiv_RO CNN Recognition
author: Stephen Hausler, Adam Jacobson, Michael Milford
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have recently been shown to excel at performing visual place recognition under changing appearance and viewpoint. Previously, place recognition has been improved by intelligently selecting relevant spatial keypoints within a convolutional layer and also by selecting the optimal layer to use. Rather than extracting features out of a particular layer, or a particular set of spatial keypoints within a layer, we propose the extraction of features using a subset of the channel dimensionality within a layer. Each feature map learns to encode a different set of weights that activate for different visual features within the set of training images. We propose a method of calibrating a CNN-based visual place recognition system, which selects the subset of feature maps that best encodes the visual features that are consistent between two different appearances of the same location. Using just 50 calibration images, all collected at the beginning of the current environment, we demonstrate a significant and consistent recognition improvement across multiple layers for two different neural networks. We evaluate our proposal on three datasets with different types of appearance changes - afternoon to morning, winter to summer and night to day. Additionally, the dimensionality reduction approach improves the computational processing speed of the recognition system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12465](http://arxiv.org/abs/1810.12465)

##### PDF
[http://arxiv.org/pdf/1810.12465](http://arxiv.org/pdf/1810.12465)

