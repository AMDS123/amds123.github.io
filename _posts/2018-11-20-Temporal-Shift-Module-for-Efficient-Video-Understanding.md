---
layout: post
title: "Temporal Shift Module for Efficient Video Understanding"
date: 2018-11-20 17:39:26
categories: arXiv_CV
tags: arXiv_CV Video_Caption Relation
author: Ji Lin, Chuang Gan, Song Han
mathjax: true
---

* content
{:toc}

##### Abstract
The explosive growth in online video streaming gives rise to challenges on efficiently extracting the spatial-temporal information to perform video understanding. Conventional 2D CNNs are computationally cheap but cannot capture long-term temporal relationships; 3D CNN based methods can achieve good performance but are computationally intensive, making it expensive to deploy. In this paper, we propose a generic and effective Temporal Shift Module (TSM) that enjoys both high efficiency and high performance. Specifically, it can achieve the performance of 3D CNN but maintain 2D complexity. The central idea of TSM is to shift part of the channels along the temporal dimension, which facilitates information exchange among neighboring frames. TSM can be inserted into 2D CNNs to achieve temporal modeling at the cost of zero FLOPs and zero parameters. On the Something-Something-V1 dataset which focuses on temporal modeling, we achieved better results than I3D family and ECO family using 6X and 2.7X fewer FLOPs respectively. Measured on P100 GPU, our single model achieved 1.8% higher accuracy at 8X lower latency and 12X higher throughput compared to I3D. Remarkably, our framework ranks the first on both Something-Something V1 and V2 leaderboards upon this paper's submission.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08383](http://arxiv.org/abs/1811.08383)

##### PDF
[http://arxiv.org/pdf/1811.08383](http://arxiv.org/pdf/1811.08383)

