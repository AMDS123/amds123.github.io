---
layout: post
title: "Temporal Deformable Convolutional Encoder-Decoder Networks for Video Captioning"
date: 2019-05-03 08:59:10
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Caption CNN Optimization RNN Relation
author: Jingwen Chen, Yingwei Pan, Yehao Li, Ting Yao, Hongyang Chao, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
It is well believed that video captioning is a fundamental but challenging task in both computer vision and artificial intelligence fields. The prevalent approach is to map an input video to a variable-length output sentence in a sequence to sequence manner via Recurrent Neural Network (RNN). Nevertheless, the training of RNN still suffers to some degree from vanishing/exploding gradient problem, making the optimization difficult. Moreover, the inherently recurrent dependency in RNN prevents parallelization within a sequence during training and therefore limits the computations. In this paper, we present a novel design --- Temporal Deformable Convolutional Encoder-Decoder Networks (dubbed as TDConvED) that fully employ convolutions in both encoder and decoder networks for video captioning. Technically, we exploit convolutional block structures that compute intermediate states of a fixed number of inputs and stack several blocks to capture long-term relationships. The structure in encoder is further equipped with temporal deformable convolution to enable free-form deformation of temporal sampling. Our model also capitalizes on temporal attention mechanism for sentence generation. Extensive experiments are conducted on both MSVD and MSR-VTT video captioning datasets, and superior results are reported when comparing to conventional RNN-based encoder-decoder techniques. More remarkably, TDConvED increases CIDEr-D performance from 58.8% to 67.2% on MSVD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01077](http://arxiv.org/abs/1905.01077)

##### PDF
[http://arxiv.org/pdf/1905.01077](http://arxiv.org/pdf/1905.01077)

