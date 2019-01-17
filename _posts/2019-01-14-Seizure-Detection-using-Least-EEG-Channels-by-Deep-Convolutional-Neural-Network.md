---
layout: post
title: "Seizure Detection using Least EEG Channels by Deep Convolutional Neural Network"
date: 2019-01-14 16:31:52
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Mustafa Talha Avcu, Zhuo Zhang, Derrick Wei Shih Chan
mathjax: true
---

* content
{:toc}

##### Abstract
This work aims to develop an end-to-end solution for seizure onset detection. We design the SeizNet, a Convolutional Neural Network for seizure detection. To compare SeizNet with traditional machine learning approach, a baseline classifier is implemented using spectrum band power features with Support Vector Machines (BPsvm). We explore the possibility to use the least number of channels for accurate seizure detection by evaluating SeizNet and BPsvm approaches using all channels and two channels settings respectively. EEG Data is acquired from 29 pediatric patients admitted to KK Woman's and Children's Hospital who were diagnosed as typical absence seizures. We conduct leave-one-out cross validation for all subjects. Using full channel data, BPsvm yields a sensitivity of 86.6\% and 0.84 false alarm (per hour) while SeizNet yields overall sensitivity of 95.8 \% with 0.17 false alarm. More interestingly, two channels seizNet outperforms full channel BPsvm with a sensitivity of 93.3\% and 0.58 false alarm. We further investigate interpretability of SeizNet by decoding the filters learned along convolutional layers. Seizure-like characteristics can be clearly observed in the filters from third and forth convolutional layers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05305](http://arxiv.org/abs/1901.05305)

##### PDF
[http://arxiv.org/pdf/1901.05305](http://arxiv.org/pdf/1901.05305)

