---
layout: post
title: "Unsupervised Detection of Anomalous Sound based on Deep Learning and the Neyman-Pearson Lemma"
date: 2018-10-22 08:20:59
categories: arXiv_SD
tags: arXiv_SD Optimization Deep_Learning Detection
author: Yuma Koizumi, Shoichiro Saito, Hisashi Uematsum Yuta Kawachi, Noboru Harada
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel optimization principle and its implementation for unsupervised anomaly detection in sound (ADS) using an autoencoder (AE). The goal of unsupervised-ADS is to detect unknown anomalous sound without training data of anomalous sound. Use of an AE as a normal model is a state-of-the-art technique for unsupervised-ADS. To decrease the false positive rate (FPR), the AE is trained to minimize the reconstruction error of normal sounds and the anomaly score is calculated as the reconstruction error of the observed sound. Unfortunately, since this training procedure does not take into account the anomaly score for anomalous sounds, the true positive rate (TPR) does not necessarily increase. In this study, we define an objective function based on the Neyman-Pearson lemma by considering ADS as a statistical hypothesis test. The proposed objective function trains the AE to maximize the TPR under an arbitrary low FPR condition. To calculate the TPR in the objective function, we consider that the set of anomalous sounds is the complementary set of normal sounds and simulate anomalous sounds by using a rejection sampling algorithm. Through experiments using synthetic data, we found that the proposed method improved the performance measures of ADS under low FPR conditions. In addition, we confirmed that the proposed method could detect anomalous sounds in real environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09133](http://arxiv.org/abs/1810.09133)

##### PDF
[http://arxiv.org/pdf/1810.09133](http://arxiv.org/pdf/1810.09133)

