---
layout: post
title: "Residual Memory Networks: Feed-forward approach to learn long temporal dependencies"
date: 2018-08-06 14:00:40
categories: arXiv_CV
tags: arXiv_CV RNN Memory_Networks Recognition
author: Murali Karthick Baskar, Martin Karafiat, Lukas Burget, Karel Vesely, Frantisek Grezl, Jan Honza Cernocky
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep recurrent neural network (RNN) architectures is complicated due to the increased network complexity. This disrupts the learning of higher order abstracts using deep RNN. In case of feed-forward networks training deep structures is simple and faster while learning long-term temporal information is not possible. In this paper we propose a residual memory neural network (RMN) architecture to model short-time dependencies using deep feed-forward layers having residual and time delayed connections. The residual connection paves way to construct deeper networks by enabling unhindered flow of gradients and the time delay units capture temporal information with shared weights. The number of layers in RMN signifies both the hierarchical processing depth and temporal depth. The computational complexity in training RMN is significantly less when compared to deep recurrent networks. RMN is further extended as bi-directional RMN (BRMN) to capture both past and future information. Experimental analysis is done on AMI corpus to substantiate the capability of RMN in learning long-term information and hierarchical information. Recognition performance of RMN trained with 300 hours of Switchboard corpus is compared with various state-of-the-art LVCSR systems. The results indicate that RMN and BRMN gains 6 % and 3.8 % relative improvement over LSTM and BLSTM networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.01916](https://arxiv.org/abs/1808.01916)

##### PDF
[https://arxiv.org/pdf/1808.01916](https://arxiv.org/pdf/1808.01916)

