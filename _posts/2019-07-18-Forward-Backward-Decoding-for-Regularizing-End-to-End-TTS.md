---
layout: post
title: "Forward-Backward Decoding for Regularizing End-to-End TTS"
date: 2019-07-18 12:24:30
categories: arXiv_CL
tags: arXiv_CL Regularization Attention
author: Yibin Zheng, Xi Wang, Lei He, Shifeng Pan, Frank K. Soong, Zhengqi Wen, Jianhua Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Neural end-to-end TTS can generate very high-quality synthesized speech, and even close to human recording within similar domain text. However, it performs unsatisfactory when scaling it to challenging test sets. One concern is that the encoder-decoder with attention-based network adopts autoregressive generative sequence model with the limitation of "exposure bias" To address this issue, we propose two novel methods, which learn to predict future by improving agreement between forward and backward decoding sequence. The first one is achieved by introducing divergence regularization terms into model training objective to reduce the mismatch between two directional models, namely L2R and R2L (which generates targets from left-to-right and right-to-left, respectively). While the second one operates on decoder-level and exploits the future information during decoding. In addition, we employ a joint training strategy to allow forward and backward decoding to improve each other in an interactive process. Experimental results show our proposed methods especially the second one (bidirectional decoder regularization), leads a significantly improvement on both robustness and overall naturalness, as outperforming baseline (the revised version of Tacotron2) with a MOS gap of 0.14 in a challenging test, and achieving close to human quality (4.42 vs. 4.49 in MOS) on general test.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09006](http://arxiv.org/abs/1907.09006)

##### PDF
[http://arxiv.org/pdf/1907.09006](http://arxiv.org/pdf/1907.09006)

