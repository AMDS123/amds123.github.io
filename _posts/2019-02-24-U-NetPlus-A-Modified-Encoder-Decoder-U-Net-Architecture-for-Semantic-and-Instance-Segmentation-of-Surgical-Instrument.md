---
layout: post
title: "U-NetPlus: A Modified Encoder-Decoder U-Net Architecture for Semantic and Instance Segmentation of Surgical Instrument"
date: 2019-02-24 18:57:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Detection
author: S. M. Kamrul Hasan, Cristian A. Linte
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional therapy approaches limit surgeons' dexterity control due to limited field-of-view. With the advent of robot-assisted surgery, there has been a paradigm shift in medical technology for minimally invasive surgery. However, it is very challenging to track the position of the surgical instruments in a surgical scene, and accurate detection &amp; identification of surgical tools is paramount. Deep learning-based semantic segmentation in frames of surgery videos has the potential to facilitate this task. In this work, we modify the U-Net architecture named U-NetPlus, by introducing a pre-trained encoder and re-design the decoder part, by replacing the transposed convolution operation with an upsampling operation based on nearest-neighbor (NN) interpolation. To further improve performance, we also employ a very fast and flexible data augmentation technique. We trained the framework on 8 x 225 frame sequences of robotic surgical videos, available through the MICCAI 2017 EndoVis Challenge dataset and tested it on 8 x 75 frame and 2 x 300 frame videos. Using our U-NetPlus architecture, we report a 90.20% DICE for binary segmentation, 76.26% DICE for instrument part segmentation, and 46.07% for instrument type (i.e., all instruments) segmentation, outperforming the results of previous techniques implemented and tested on these data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08994](http://arxiv.org/abs/1902.08994)

##### PDF
[http://arxiv.org/pdf/1902.08994](http://arxiv.org/pdf/1902.08994)

