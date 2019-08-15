---
layout: post
title: "Interleaved Multitask Learning for Audio Source Separation with Independent Databases"
date: 2019-08-14 15:56:34
categories: arXiv_SD
tags: arXiv_SD Optimization Inference
author: Clement S. J. Doire, Olumide Okubadejo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Network-based source separation methods usually train independent models to optimize for the separation of individual sources. Although this can lead to good performance for well-defined targets, it can also be computationally expensive. The multitask alternative of a single network jointly optimizing for all targets simultaneously usually requires the availability of all target sources for each input. This requirement hampers the ability to create large training databases. In this paper, we present a model that decomposes the learnable parameters into a shared parametric model (encoder) and independent components (decoders) specific to each source. We propose an interleaved training procedure that optimizes the sub-task decoders independently and thus does not require each sample to possess a ground truth for all of its composing sources. Experimental results on MUSDB18 with the proposed method show comparable performance to independently trained models, with less trainable parameters, more efficient inference, and an encoder transferable to future target objectives. The results also show that using the proposed interleaved training procedure leads to better Source-to-Interference energy ratios when compared to the simultaneous optimization of all training objectives, even when all composing sources are available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05182](http://arxiv.org/abs/1908.05182)

##### PDF
[http://arxiv.org/pdf/1908.05182](http://arxiv.org/pdf/1908.05182)

