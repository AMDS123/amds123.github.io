---
layout: post
title: "Channel adversarial training for cross-channel text-independent speaker recognition"
date: 2019-02-25 03:32:58
categories: arXiv_SD
tags: arXiv_SD Adversarial Recognition
author: Xin Fang, Liang Zou, Jin Li, Lei Sun, Zhen-Hua Ling
mathjax: true
---

* content
{:toc}

##### Abstract
The conventional speaker recognition frameworks (e.g., the i-vector and CNN-based approach) have been successfully applied to various tasks when the channel of the enrolment dataset is similar to that of the test dataset. However, in real-world applications, mismatch always exists between these two datasets, which may severely deteriorate the recognition performance. Previously, a few channel compensation algorithms have been proposed, such as Linear Discriminant Analysis (LDA) and Probabilistic LDA. However, these methods always require the collections of different channels from a specific speaker, which is unrealistic to be satisfied in real scenarios. Inspired by domain adaptation, we propose a novel deep-learning based speaker recognition framework to learn the channel-invariant and speaker-discriminative speech representations via channel adversarial training. Specifically, we first employ a gradient reversal layer to remove variations across different channels. Then, the compressed information is projected into the same subspace by adversarial training. Experiments on test datasets with 54,133 speakers demonstrate that the proposed method is not only effective at alleviating the channel mismatch problem, but also outperforms state-of-the-art speaker recognition methods. Compared with the i-vector-based method and the CNN-based method, our proposed method achieves significant relative improvement of 44.7% and 22.6% respectively in terms of the Top1 recall.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09074](http://arxiv.org/abs/1902.09074)

##### PDF
[http://arxiv.org/pdf/1902.09074](http://arxiv.org/pdf/1902.09074)

