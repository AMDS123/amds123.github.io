---
layout: post
title: "Batch Uniformization for Minimizing Maximum Anomaly Score of DNN-based Anomaly Detection in Sounds"
date: 2019-07-19 01:58:20
categories: arXiv_SD
tags: arXiv_SD Detection
author: Yuma Koizumi, Shoichiro Saito, Masataka Yamaguchi, Shin Murata, Noboru Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Use of an autoencoder (AE) as a normal model is a state-of-the-art technique for unsupervised-anomaly detection in sounds (ADS). The AE is trained to minimize the sample mean of the anomaly score of normal sounds in a mini-batch. One problem with this approach is that the anomaly score of rare-normal sounds becomes higher than that of frequent-normal sounds, because the sample mean is strongly affected by frequent-normal samples, resulting in preferentially decreasing the anomaly score of frequent-normal samples. To decrease anomaly scores for both frequent- and rare-normal sounds, we propose batch uniformization, a training method for unsupervised-ADS for minimizing a weighted average of the anomaly score on each sample in a mini-batch. We used the reciprocal of the probabilistic density of each sample as the weight, more intuitively, a large weight is given for rare-normal sounds. Such a weight works to give a constant anomaly score for both frequent- and rare-normal sounds. Since the probabilistic density is unknown, we estimate it by using the kernel density estimation on each training mini-batch. Verification- and objective-experiments show that the proposed batch uniformization improves the performance of unsupervised-ADS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08338](http://arxiv.org/abs/1907.08338)

##### PDF
[http://arxiv.org/pdf/1907.08338](http://arxiv.org/pdf/1907.08338)

