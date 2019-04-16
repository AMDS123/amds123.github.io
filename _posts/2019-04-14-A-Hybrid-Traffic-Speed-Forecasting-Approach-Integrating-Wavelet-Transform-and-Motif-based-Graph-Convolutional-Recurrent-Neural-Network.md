---
layout: post
title: "A Hybrid Traffic Speed Forecasting Approach Integrating Wavelet Transform and Motif-based Graph Convolutional Recurrent Neural Network"
date: 2019-04-14 08:40:58
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction Relation
author: Na Zhang, Xuefeng Guan, Jun Cao, Xinglei Wang, Huayi Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Traffic forecasting is crucial for urban traffic management and guidance. However, existing methods rarely exploit the time-frequency properties of traffic speed observations, and often neglect the propagation of traffic flows from upstream to downstream road segments. In this paper, we propose a hybrid approach that learns the spatio-temporal dependency in traffic flows and predicts short-term traffic speeds on a road network. Specifically, we employ wavelet transform to decompose raw traffic data into several components with different frequency sub-bands. A Motif-based Graph Convolutional Recurrent Neural Network (Motif-GCRNN) and Auto-Regressive Moving Average (ARMA) are used to train and predict low-frequency components and high-frequency components, respectively. In the Motif-GCRNN framework, we integrate Graph Convolutional Networks (GCNs) with local sub-graph structures - Motifs - to capture the spatial correlations among road segments, and apply Long Short-Term Memory (LSTM) to extract the short-term and periodic patterns in traffic speeds. Experiments on a traffic dataset collected in Chengdu, China, demonstrate that the proposed hybrid method outperforms six state-of-art prediction methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06656](http://arxiv.org/abs/1904.06656)

##### PDF
[http://arxiv.org/pdf/1904.06656](http://arxiv.org/pdf/1904.06656)

