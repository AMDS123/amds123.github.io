---
layout: post
title: "Relational Network for Skeleton-Based Action Recognition"
date: 2019-04-11 12:36:13
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition CNN RNN Relation Recognition
author: Wu Zheng, Lin Li, Zhaoxiang Zhang, Yan Huang, Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With the fast development of effective and low-cost human skeleton capture systems, skeleton-based action recognition has attracted much attention recently. Most existing methods use Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) to extract spatio-temporal information embedded in the skeleton sequences for action recognition. However, these approaches are limited in the ability of relational modeling in a single skeleton, due to the loss of important structural information when converting the raw skeleton data to adapt to the input format of CNN or RNN. In this paper, we propose an Attentional Recurrent Relational Network-LSTM (ARRN-LSTM) to simultaneously model spatial configurations and temporal dynamics in skeletons for action recognition. We introduce the Recurrent Relational Network to learn the spatial features in a single skeleton, followed by a multi-layer LSTM to learn the temporal features in the skeleton sequences. Between the two modules, we design an adaptive attentional module to focus attention on the most discriminative parts in the single skeleton. To exploit the complementarity from different geometries in the skeleton for sufficient relational modeling, we design a two-stream architecture to learn the structural features among joints and lines simultaneously. Extensive experiments are conducted on several popular skeleton datasets and the results show that the proposed approach achieves better results than most mainstream methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.02556](http://arxiv.org/abs/1805.02556)

##### PDF
[http://arxiv.org/pdf/1805.02556](http://arxiv.org/pdf/1805.02556)

