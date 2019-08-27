---
layout: post
title: "Non-local Recurrent Neural Memory for Supervised Sequence Modeling"
date: 2019-08-26 09:01:57
categories: arXiv_CV
tags: arXiv_CV Sentiment Action_Recognition RNN Recognition
author: Canmiao Fu, Wenjie Pei, Qiong Cao, Chaopeng Zhang, Yong Zhao, Xiaoyong Shen, Yu-Wing Tai
mathjax: true
---

* content
{:toc}

##### Abstract
Typical methods for supervised sequence modeling are built upon the recurrent neural networks to capture temporal dependencies. One potential limitation of these methods is that they only model explicitly information interactions between adjacent time steps in a sequence, hence the high-order interactions between nonadjacent time steps are not fully exploited. It greatly limits the capability of modeling the long-range temporal dependencies since one-order interactions cannot be maintained for a long term due to information dilution and gradient vanishing. To tackle this limitation, we propose the Non-local Recurrent Neural Memory (NRNM) for supervised sequence modeling, which performs non-local operations to learn full-order interactions within a sliding temporal block and models global interactions between blocks in a gated recurrent manner. Consequently, our model is able to capture the long-range dependencies. Besides, the latent high-level features contained in high-order interactions can be distilled by our model. We demonstrate the merits of our NRNM on two different tasks: action recognition and sentiment analysis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09535](http://arxiv.org/abs/1908.09535)

##### PDF
[http://arxiv.org/pdf/1908.09535](http://arxiv.org/pdf/1908.09535)

