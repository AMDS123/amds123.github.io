---
layout: post
title: "Towards Linear Time Neural Machine Translation with Capsule Networks"
date: 2018-11-01 09:37:48
categories: arXiv_CL
tags: arXiv_CL Knowledge NMT RNN
author: Mingxuan Wang, Jun Xie, Zhixing Tan, Jinsong Su, Deyi xiong, Chao bian
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we first investigate a novel capsule network with dynamic routing for linear time Neural Machine Translation (NMT), referred as \textsc{CapsNMT}. \textsc{CapsNMT} uses an aggregation mechanism to map the source sentence into a matrix with pre-determined size, and then applys a deep LSTM network to decode the target sequence from the source representation. Unlike the previous work \cite{sutskever2014sequence} to store the source sentence with a passive and bottom-up way, the dynamic routing policy encodes the source sentence with an iterative process to decide the credit attribution between nodes from lower and higher layers. \textsc{CapsNMT} has two core properties: it runs in time that is linear in the length of the sequences and provides a more flexible way to select, represent and aggregates the part-whole information of the source sentence. On WMT14 English-German task and a larger WMT14 English-French task, \textsc{CapsNMT} achieves comparable results with the state-of-the-art NMT systems. To the best of our knowledge, this is the first work that capsule networks have been empirically investigated for sequence to sequence problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00287](http://arxiv.org/abs/1811.00287)

##### PDF
[http://arxiv.org/pdf/1811.00287](http://arxiv.org/pdf/1811.00287)

