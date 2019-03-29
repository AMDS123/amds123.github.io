---
layout: post
title: "TSM: Temporal Shift Module for Efficient Video Understanding"
date: 2019-03-28 04:04:00
categories: arXiv_CV
tags: arXiv_CV Video_Caption Relation Recognition
author: Ji Lin, Chuang Gan, Song Han
mathjax: true
---

* content
{:toc}

##### Abstract
The explosive growth in video streaming gives rise to challenges on efficiently extracting the spatial-temporal information to perform video understanding at low computation cost. Conventional 2D CNNs are computationally cheap but cannot capture temporal relationships; 3D CNN based methods can achieve good performance but are computationally intensive, making it expensive to deploy. In this paper, we propose a generic and effective Temporal Shift Module (TSM) that enjoys both high efficiency and high performance. Specifically, it can achieve the performance of 3D CNN but maintain 2D CNN's complexity. TSM shifts part of the channels along the temporal dimension, thus facilitate information exchanged among neighboring frames. It can be inserted into 2D CNNs to achieve temporal modeling at zero computation and zero parameters. We also extended TSM to online video recognition setting, which enables real-time low-latency online video recognition. On the Something-Something-V1 dataset which focuses on temporal modeling, we achieved better results than I3D family and ECO family using 6X and 2.7X fewer FLOPs respectively. Measured on P100 GPU, our single model achieved 1.8% higher accuracy at 9.5X lower latency and 12.7X higher throughput compared to I3D. The code is available here: https://github.com/MIT-HAN-LAB/temporal-shift-module.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08383](http://arxiv.org/abs/1811.08383)

##### PDF
[http://arxiv.org/pdf/1811.08383](http://arxiv.org/pdf/1811.08383)

