---
layout: post
title: "CameraNet: A Two-Stage Framework for Effective Camera ISP Learning"
date: 2019-08-05 06:13:31
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhetong Liang, Jianrui Cai, Zisheng Cao, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional image signal processing (ISP) pipeline consists of a set of individual image processing components onboard a camera to reconstruct a high-quality sRGB image from the sensor raw data. Due to the hand-crafted nature of the ISP components, traditional ISP pipeline has limited reconstruction quality under challenging scenes. Recently, the convolutional neural networks (CNNs) have demonstrated their competitiveness in solving many individual image processing problems, such as image denoising, demosaicking, white balance and contrast enhancement. However, it remains a question whether a CNN model can address the multiple tasks inside an ISP pipeline simultaneously. We make a good attempt along this line and propose a novel framework, which we call CameraNet, for effective and general ISP pipeline learning. The CameraNet is composed of two CNN modules to account for two sets of relatively uncorrelated subtasks in an ISP pipeline: restoration and enhancement. To train the two-stage CameraNet model, we specify two groundtruths that can be easily created in the common workflow of photography. CameraNet is trained to progressively address the restoration and the enhancement subtasks with its two modules. Experiments show that the proposed CameraNet achieves consistently compelling reconstruction quality on three benchmark datasets and outperforms traditional ISP pipelines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01481](http://arxiv.org/abs/1908.01481)

##### PDF
[http://arxiv.org/pdf/1908.01481](http://arxiv.org/pdf/1908.01481)

