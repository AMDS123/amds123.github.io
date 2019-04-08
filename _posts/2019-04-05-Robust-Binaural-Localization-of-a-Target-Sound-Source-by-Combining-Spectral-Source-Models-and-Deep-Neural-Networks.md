---
layout: post
title: "Robust Binaural Localization of a Target Sound Source by Combining Spectral Source Models and Deep Neural Networks"
date: 2019-04-05 11:50:25
categories: arXiv_SD
tags: arXiv_SD Knowledge Attention
author: Ning Ma, Jose A. Gonzalez, Guy J. Brown
mathjax: true
---

* content
{:toc}

##### Abstract
Despite there being clear evidence for top-down (e.g., attentional) effects in biological spatial hearing, relatively few machine hearing systems exploit top-down model-based knowledge in sound localisation. This paper addresses this issue by proposing a novel framework for binaural sound localisation that combines model-based information about the spectral characteristics of sound sources and deep neural networks (DNNs). A target source model and a background source model are first estimated during a training phase using spectral features extracted from sound signals in isolation. When the identity of the background source is not available, a universal background model can be used. During testing, the source models are used jointly to explain the mixed observations and improve the localisation process by selectively weighting source azimuth posteriors output by a DNN-based localisation system. To address the possible mismatch between training and testing, a model adaptation process is further employed on-the-fly during testing, which adapts the background model parameters directly from the noisy observations in an iterative manner. The proposed system therefore combines model-based and data-driven information flow within a single computational framework. The evaluation task involved localisation of a target speech source in the presence of an interfering source and room reverberation. Our experiments show that by exploiting model-based information in this way, sound localisation performance can be improved substantially under various noisy and reverberant conditions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.03006](https://arxiv.org/abs/1904.03006)

##### PDF
[https://arxiv.org/pdf/1904.03006](https://arxiv.org/pdf/1904.03006)

