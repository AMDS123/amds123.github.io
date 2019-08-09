---
layout: post
title: "Bayesian Feature Pyramid Networks for Automatic Multi-Label Segmentation of Chest X-rays and Assessment of Cardio-Thoratic Ratio"
date: 2019-08-08 04:16:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Roman Solovyev, Iaroslav Melekhov, Timo Lesonen, Elias Vaattovaara, Osmo Tervonen, Aleksei Tiulpin
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiothoratic ratio (CTR) estimated from chest radiographs is a marker indicative of cardiomegaly, the presence of which is in the criteria for heart failure diagnosis. Existing methods for automatic assessment of CTR are driven by Deep Learning-based segmentation. However, these techniques produce only point estimates of CTR but clinical decision making typically assumes the uncertainty. In this paper, we propose a novel method for chest X-ray segmentation and CTR assessment in an automatic manner. In contrast to the previous art, we, for the first time, propose to estimate CTR with uncertainty bounds. Our method is based on Deep Convolutional Neural Network with Feature Pyramid Network (FPN) decoder. We propose two modifications of FPN: replace the batch normalization with instance normalization and inject the dropout which allows to obtain the Monte-Carlo estimates of the segmentation maps at test time. Finally, using the predicted segmentation mask samples, we estimate CTR with uncertainty. In our experiments we demonstrate that the proposed method generalizes well to three different test sets. Finally, we make the annotations produced by two radiologists for all our datasets publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02924](http://arxiv.org/abs/1908.02924)

##### PDF
[http://arxiv.org/pdf/1908.02924](http://arxiv.org/pdf/1908.02924)

