---
layout: post
title: "Hierarchical Generative Modeling for Controllable Speech Synthesis"
date: 2018-10-16 18:20:02
categories: arXiv_CL
tags: arXiv_CL
author: Wei-Ning Hsu, Yu Zhang, Ron J. Weiss, Heiga Zen, Yonghui Wu, Yuxuan Wang, Yuan Cao, Ye Jia, Zhifeng Chen, Jonathan Shen, Patrick Nguyen, Ruoming Pang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a neural end-to-end text-to-speech (TTS) model which can control latent attributes in the generated speech that are rarely annotated in the training data, such as speaking style, accent, background noise, and recording conditions. The model is formulated as a conditional generative model with two levels of hierarchical latent variables. The first level is a categorical variable, which represents attribute groups (e.g. clean/noisy) and provides interpretability. The second level, conditioned on the first, is a multivariate Gaussian variable, which characterizes specific attribute configurations (e.g. noise level, speaking rate) and enables disentangled fine-grained control over these attributes. This amounts to using a Gaussian mixture model (GMM) for the latent distribution. Extensive evaluation demonstrates its ability to control the aforementioned attributes. In particular, it is capable of consistently synthesizing high-quality clean speech regardless of the quality of the training data for the target speaker.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07217](http://arxiv.org/abs/1810.07217)

##### PDF
[http://arxiv.org/pdf/1810.07217](http://arxiv.org/pdf/1810.07217)

