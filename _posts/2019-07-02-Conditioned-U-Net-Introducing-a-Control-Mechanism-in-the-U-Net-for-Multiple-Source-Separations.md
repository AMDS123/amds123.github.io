---
layout: post
title: "Conditioned-U-Net: Introducing a Control Mechanism in the U-Net for Multiple Source Separations"
date: 2019-07-02 10:10:53
categories: arXiv_SD
tags: arXiv_SD
author: Gabriel Meseguer-Brocal, Geoffroy Peeters
mathjax: true
---

* content
{:toc}

##### Abstract
Data-driven models for audio source separation such as U-Net or Wave-U-Net are usually models dedicated to and specifically trained for a single task, e.g. a particular instrument isolation. Training them for various tasks at once commonly results in worse performances than training them for a single specialized task. In this work, we introduce the Conditioned-U-Net (C-U-Net) which adds a control mechanism to the standard U-Net. The control mechanism allows us to train a unique and generic U-Net to perform the separation of various instruments. The C-U-Net decides the instrument to isolate according to a one-hot-encoding input vector. The input vector is embedded to obtain the parameters that control Feature-wise Linear Modulation (FiLM) layers. FiLM layers modify the U-Net feature maps in order to separate the desired instrument via affine transformations. The C-U-Net performs different instrument separations, all with a single model achieving the same performances as the dedicated ones at a lower cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01277](http://arxiv.org/abs/1907.01277)

##### PDF
[http://arxiv.org/pdf/1907.01277](http://arxiv.org/pdf/1907.01277)

