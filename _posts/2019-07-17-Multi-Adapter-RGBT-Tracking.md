---
layout: post
title: "Multi-Adapter RGBT Tracking"
date: 2019-07-17 12:51:37
categories: arXiv_CV
tags: arXiv_CV Attention Tracking CNN
author: Chenglong Li, Andong Lu, Aihua Zheng, Zhengzheng Tu, Jin Tang
mathjax: true
---

* content
{:toc}

##### Abstract
The task of RGBT tracking aims to take the complementary advantages from visible spectrum and thermal infrared data to achieve robust visual tracking, and receives more and more attention in recent years. Existing works focus on modality-specific information integration by introducing modality weights to achieve adaptive fusion or learning robust feature representations of different modalities. Although these methods could effectively deploy the modality-specific properties, they ignore the potential values of modality-shared cues as well as instance-aware information, which are crucial for effective fusion of different modalities in RGBT tracking. In this paper, we propose a novel Multi-Adapter convolutional Network (MANet) to jointly perform modality-shared, modality-specific and instance-aware feature learning in an end-to-end trained deep framework for RGBT tracking. We design three kinds of adapters within our network. In a specific, the generality adapter is to extract shared object representations, the modality adapter aims at encoding modality-specific information to deploy their complementary advantages, and the instance adapter is to model the appearance properties and temporal variations of a certain object. Moreover, to reduce computational complexity for real-time demand of visual tracking, we design a parallel structure of generic adapter and modality adapter. Extensive experiments on two RGBT tracking benchmark datasets demonstrate the outstanding performance of the proposed tracker against other state-of-the-art RGB and RGBT tracking algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07485](http://arxiv.org/abs/1907.07485)

##### PDF
[http://arxiv.org/pdf/1907.07485](http://arxiv.org/pdf/1907.07485)

