---
layout: post
title: "From Here to There: Video Inbetweening Using Direct 3D Convolutions"
date: 2019-05-24 14:01:08
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN RNN Quantitative
author: Yunpeng Li, Dominik Roblek, Marco Tagliasacchi
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of generating plausible and diverse video sequences, when we are only given a start and an end frame. This task is also known as inbetweening, and it belongs to the broader area of stochastic video generation, which is generally approached by means of recurrent neural networks (RNN). In this paper, we propose instead a fully convolutional model to generate video sequences directly in the pixel domain. We first obtain a latent video representation using a stochastic fusion mechanism that learns how to incorporate information from the start and end frames. Our model learns to produce such latent representation by progressively increasing the temporal resolution, and then decode in the spatiotemporal domain using 3D convolutions. The model is trained end-to-end by minimizing an adversarial loss. Experiments on several widely-used benchmark datasets show that it is able to generate meaningful and diverse in-between video sequences, according to both quantitative and qualitative evaluations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10240](http://arxiv.org/abs/1905.10240)

##### PDF
[http://arxiv.org/pdf/1905.10240](http://arxiv.org/pdf/1905.10240)

