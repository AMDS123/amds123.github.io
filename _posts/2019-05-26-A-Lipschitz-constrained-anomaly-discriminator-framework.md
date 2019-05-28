---
layout: post
title: "A Lipschitz-constrained anomaly discriminator framework"
date: 2019-05-26 01:57:42
categories: arXiv_AI
tags: arXiv_AI Object_Detection GAN Detection
author: Alexander Tong, Guy Wolf, Smita Krishnaswamy
mathjax: true
---

* content
{:toc}

##### Abstract
Anomaly detection is a problem of great interest in medicine, finance, and other fields where error and fraud need to be detected and corrected. Most deep anomaly detection methods rely on autoencoder reconstruction error. However, we show that this approach has limited value. First, this approach starts to perform poorly when either noise or anomalies contaminate training data, even to a small extent. Second, this approach cannot detect anomalous but simple to reconstruct points. This can be seen even in relatively simple examples, such as feeding a black image to detectors trained on MNIST digits. Here, we introduce a new discriminator-based unsupervised Lipschitz anomaly detector (LAD). We train a Wasserstein discriminator, similar to the ones used in GANs, to detect the difference between the training data and corruptions of the training data. We show that this procedure successfully detects unseen anomalies with guarantees on those that have a certain Wasserstein distance from the data or corrupted training set. Finally, we show results of this system in an electronic medical record dataset of HIV-positive veterans from the veterans aging cohort study (VACS) to establish usability in a medical setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10710](http://arxiv.org/abs/1905.10710)

##### PDF
[http://arxiv.org/pdf/1905.10710](http://arxiv.org/pdf/1905.10710)

