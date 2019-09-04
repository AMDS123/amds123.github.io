---
layout: post
title: "Towards Making a Dependency Parser See"
date: 2019-09-03 10:42:35
categories: arXiv_CL
tags: arXiv_CL Tracking Inference RNN
author: Michalina Strzyz, David Vilares, Carlos Gómez-Rodríguez
mathjax: true
---

* content
{:toc}

##### Abstract
We explore whether it is possible to leverage eye-tracking data in an RNN dependency parser (for English) when such information is only available during training, i.e., no aggregated or token-level gaze features are used at inference time. To do so, we train a multitask learning model that parses sentences as sequence labeling and leverages gaze features as auxiliary tasks. Our method also learns to train from disjoint datasets, i.e. it can be used to test whether already collected gaze features are useful to improve the performance on new non-gazed annotated treebanks. Accuracy gains are modest but positive, showing the feasibility of the approach. It can serve as a first step towards architectures that can better leverage eye-tracking data or other complementary information available only for training sentences, possibly leading to improvements in syntactic parsing.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01053](https://arxiv.org/abs/1909.01053)

##### PDF
[https://arxiv.org/pdf/1909.01053](https://arxiv.org/pdf/1909.01053)

