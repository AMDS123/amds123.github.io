---
layout: post
title: "AdaFlow: Domain-Adaptive Density Estimator with Application to Anomaly Detection and Unpaired Cross-Domain Translation"
date: 2018-12-14 06:40:02
categories: arXiv_SD
tags: arXiv_SD Attention Detection
author: Masataka Yamaguchi, Yuma Koizumi, Noboru Harada
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle unsupervised anomaly detection (UAD), a problem of detecting data that significantly differ from normal data. UAD is typically solved by using density estimation. Recently, deep neural network (DNN)-based density estimators, such as Normalizing Flows, have been attracting attention. However, one of their drawbacks is the difficulty in adapting them to the change in the normal data's distribution. To address this difficulty, we propose AdaFlow, a new DNN-based density estimator that can be easily adapted to the change of the distribution. AdaFlow is a unified model of a Normalizing Flow and Adaptive Batch-Normalizations, a module that enables DNNs to adapt to new distributions. AdaFlow can be adapted to a new distribution by just conducting forward propagation once per sample; hence, it can be used on devices that have limited computational resources. We have confirmed the effectiveness of the proposed model through an anomaly detection in a sound task. We also propose a method of applying AdaFlow to the unpaired cross-domain translation problem, in which one has to train a cross-domain translation model with only unpaired samples. We have confirmed that our model can be used for the cross-domain translation problem through experiments on image datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05796](http://arxiv.org/abs/1812.05796)

##### PDF
[http://arxiv.org/pdf/1812.05796](http://arxiv.org/pdf/1812.05796)

