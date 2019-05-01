---
layout: post
title: "Early Action Prediction with Generative Adversarial Networks"
date: 2019-04-30 07:36:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN RNN Prediction Recognition
author: Dong Wang, Yuan Yuan, Qi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Action Prediction is aimed to determine what action is occurring in a video as early as possible, which is crucial to many online applications, such as predicting a traffic accident before it happens and detecting malicious actions in the monitoring system. In this work, we address this problem by developing an end-to-end architecture that improves the discriminability of features of partially observed videos by assimilating them to features from complete videos. For this purpose, the generative adversarial network is introduced for tackling action prediction problem, which improves the recognition accuracy of partially observed videos though narrowing the feature difference of partially observed videos from complete ones. Specifically, its generator comprises of two networks: a CNN for feature extraction and an LSTM for estimating residual error between features of the partially observed videos and complete ones, and then the features from CNN adds the residual error from LSTM, which is regarded as the enhanced feature to fool a competing discriminator. Meanwhile, the generator is trained with an additional perceptual objective, which forces the enhanced features of partially observed videos are discriminative enough for action prediction. Extensive experimental results on UCF101, BIT and UT-Interaction datasets demonstrate that our approach outperforms the state-of-the-art methods, especially for videos that less than 50% portion of frames is observed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13085](http://arxiv.org/abs/1904.13085)

##### PDF
[http://arxiv.org/pdf/1904.13085](http://arxiv.org/pdf/1904.13085)

