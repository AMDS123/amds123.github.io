---
layout: post
title: "Spatio-Temporal Adversarial Learning for Detecting Unseen Falls"
date: 2019-05-19 22:19:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Detection
author: Shehroz S. Khan, Jacob Nogas, Alex Mihailidis
mathjax: true
---

* content
{:toc}

##### Abstract
Fall detection is an important problem from both the health and machine learning perspective. A fall can lead to severe injuries, long term impairments or even death in some cases. In terms of machine learning, it presents a severely class imbalance problem with very few or no training data for falls owing to the fact that falls occur rarely. In this paper, we take an alternate philosophy to detect falls in the absence of their training data, by training the classifier on only the normal activities (that are available in abundance) and identifying a fall as an anomaly. To realize such a classifier, we use an adversarial learning framework, which comprises of a spatio-temporal autoencoder for reconstructing input video frames and a spatio-temporal convolution network to discriminate them against original video frames. 3D convolutions are used to learn spatial and temporal features from the input video frames. The adversarial learning of the spatio-temporal autoencoder will enable reconstructing the normal activities of daily living efficiently; thus, rendering detecting unseen falls plausible within this framework. We tested the performance of the proposed framework on camera sensing modalities that may preserve an individual's privacy (fully or partially), such as thermal and depth camera. Our results on three publicly available datasets show that the proposed spatio-temporal adversarial framework performed better than other frame based (or spatial) adversarial learning methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07817](http://arxiv.org/abs/1905.07817)

##### PDF
[http://arxiv.org/pdf/1905.07817](http://arxiv.org/pdf/1905.07817)

