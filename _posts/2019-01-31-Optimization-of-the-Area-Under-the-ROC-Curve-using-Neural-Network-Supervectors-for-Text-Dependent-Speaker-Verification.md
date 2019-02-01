---
layout: post
title: "Optimization of the Area Under the ROC Curve using Neural Network Supervectors for Text-Dependent Speaker Verification"
date: 2019-01-31 12:37:57
categories: arXiv_SD
tags: arXiv_SD Optimization Detection
author: Victoria Mingote, Antonio Miguel, Alfonso Ortega, Eduardo Lleida
mathjax: true
---

* content
{:toc}

##### Abstract
This paper explores two techniques to improve the performance of text-dependent speaker verification systems based on deep neural networks. Firstly, we propose a general alignment mechanism to keep the temporal structure of each phrase and obtain a supervector with the speaker and phrase information, since both are relevant for a text-dependent verification. As we show, it is possible to use different alignment techniques to replace the average pooling providing significant gains in performance. Moreover, we present a novel back-end approach to train a neural network for detection tasks by optimizing the Area Under the Curve (AUC) as an alternative to the usual triplet loss function, so the system is end-to-end, with a cost function closed to our desired measure of performance. As we can see in the experimental section, this approach improves the system performance, since our triplet AUC neural network learns how to discriminate between pairs of examples from the same identity and pairs of different identities. The different alignment techniques to produce supervectors in addition to the new back-end approach were tested on the RSR2015-Part I database for text-dependent speaker verification, providing competitive results compared to similar size networks using the average pooling to extract supervectors and using a simple back-end or triplet loss training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11332](http://arxiv.org/abs/1901.11332)

##### PDF
[http://arxiv.org/pdf/1901.11332](http://arxiv.org/pdf/1901.11332)

