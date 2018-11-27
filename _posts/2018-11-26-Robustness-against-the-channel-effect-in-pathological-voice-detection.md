---
layout: post
title: "Robustness against the channel effect in pathological voice detection"
date: 2018-11-26 14:11:12
categories: arXiv_SD
tags: arXiv_SD Adversarial Knowledge RNN Detection
author: Yi-Te Hsu, Zining Zhu, Chi-Te Wang, Shih-Hau Fang, Frank Rudzicz, Yu Tsao
mathjax: true
---

* content
{:toc}

##### Abstract
Many people are suffering from voice disorders, which can adversely affect the quality of their lives. In response, some researchers have proposed algorithms for automatic assessment of these disorders, based on voice signals. However, these signals can be sensitive to the recording devices. Indeed, the channel effect is a pervasive problem in machine learning for healthcare. In this study, we propose a detection system for pathological voice, which is robust against the channel effect. This system is based on a bidirectional LSTM network. To increase the performance robustness against channel mismatch, we integrate domain adversarial training (DAT) to eliminate the differences between the devices. When we train on data recorded on a high-quality microphone and evaluate on smartphone data without labels, our robust detection system increases the PR-AUC from 0.8448 to 0.9455 (and 0.9522 with target sample labels). To the best of our knowledge, this is the first study applying unsupervised domain adaptation to pathological voice detection. Notably, our system does not need target device sample labels, which allows for generalization to many new devices.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10376](http://arxiv.org/abs/1811.10376)

##### PDF
[http://arxiv.org/pdf/1811.10376](http://arxiv.org/pdf/1811.10376)

