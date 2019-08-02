---
layout: post
title: "Quality Assessment of In-the-Wild Videos"
date: 2019-08-01 13:08:04
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Classification
author: Dingquan Li, Tingting Jiang, Ming Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Quality assessment of in-the-wild videos is a challenging problem because of the absence of reference videos and shooting distortions. Knowledge of the human visual system can help establish methods for objective quality assessment of in-the-wild videos. In this work, we show two eminent effects of the human visual system, namely, content-dependency and temporal-memory effects, could be used for this purpose. We propose an objective no-reference video quality assessment method by integrating both effects into a deep neural network. For content-dependency, we extract features from a pre-trained image classification neural network for its inherent content-aware property. For temporal-memory effects, long-term dependencies, especially the temporal hysteresis, are integrated into the network with a gated recurrent unit and a subjectively-inspired temporal pooling layer. To validate the performance of our method, experiments are conducted on three publicly available in-the-wild video quality assessment databases: KoNViD-1k, CVD2014, and LIVE-Qualcomm, respectively. Experimental results demonstrate that our proposed method outperforms five state-of-the-art methods by a large margin, specifically, 12.39%, 15.71%, 15.45%, and 18.09% overall performance improvements over the second-best method VBLIINDS, in terms of SROCC, KROCC, PLCC and RMSE, respectively. Moreover, the ablation study verifies the crucial role of both the content-aware features and the modeling of temporal-memory effects. The PyTorch implementation of our method is released at https://github.com/lidq92/VSFA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00375](http://arxiv.org/abs/1908.00375)

##### PDF
[http://arxiv.org/pdf/1908.00375](http://arxiv.org/pdf/1908.00375)

