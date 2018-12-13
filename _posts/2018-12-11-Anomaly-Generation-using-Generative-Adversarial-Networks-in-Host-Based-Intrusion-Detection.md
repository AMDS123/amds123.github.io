---
layout: post
title: "Anomaly Generation using Generative Adversarial Networks in Host Based Intrusion Detection"
date: 2018-12-11 21:21:09
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Detection
author: Milad Salem, Shayan Taheri, Jiann Shiun Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks have been able to generate striking results in various domains. This generation capability can be general while the networks gain deep understanding regarding the data distribution. In many domains, this data distribution consists of anomalies and normal data, with the anomalies commonly occurring relatively less, creating datasets that are imbalanced. The capabilities that generative adversarial networks offer can be leveraged to examine these anomalies and help alleviate the challenge that imbalanced datasets propose via creating synthetic anomalies. This anomaly generation can be specifically beneficial in domains that have costly data creation processes as well as inherently imbalanced datasets. One of the domains that fits this description is the host-based intrusion detection domain. In this work, ADFA-LD dataset is chosen as the dataset of interest containing system calls of small foot-print next generation attacks. The data is first converted into images, and then a Cycle-GAN is used to create images of anomalous data from images of normal data. The generated data is combined with the original dataset and is used to train a model to detect anomalies. By doing so, it is shown that the classification results are improved, with the AUC rising from 0.55 to 0.71, and the anomaly detection rate rising from 17.07% to 80.49%. The results are also compared to SMOTE, showing the potential presented by generative adversarial networks in anomaly generation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04697](http://arxiv.org/abs/1812.04697)

##### PDF
[http://arxiv.org/pdf/1812.04697](http://arxiv.org/pdf/1812.04697)

