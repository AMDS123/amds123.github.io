---
layout: post
title: "Sparsely Aggregated Convolutional Networks"
date: 2019-02-07 07:51:35
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Ligeng Zhu, Ruizhi Deng, Michael Maire, Zhiwei Deng, Greg Mori, Ping Tan
mathjax: true
---

* content
{:toc}

##### Abstract
We explore a key architectural aspect of deep convolutional neural networks: the pattern of internal skip connections used to aggregate outputs of earlier layers for consumption by deeper layers. Such aggregation is critical to facilitate training of very deep networks in an end-to-end manner. This is a primary reason for the widespread adoption of residual networks, which aggregate outputs via cumulative summation. While subsequent works investigate alternative aggregation operations (e.g. concatenation), we focus on an orthogonal question: which outputs to aggregate at a particular point in the network. We propose a new internal connection structure which aggregates only a sparse set of previous outputs at any given depth. Our experiments demonstrate this simple design change offers superior performance with fewer parameters and lower computational requirements. Moreover, we show that sparse aggregation allows networks to scale more robustly to 1000+ layers, thereby opening future avenues for training long-running visual processes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.05895](http://arxiv.org/abs/1801.05895)

##### PDF
[http://arxiv.org/pdf/1801.05895](http://arxiv.org/pdf/1801.05895)

