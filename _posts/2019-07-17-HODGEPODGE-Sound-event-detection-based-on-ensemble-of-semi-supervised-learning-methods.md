---
layout: post
title: "HODGEPODGE: Sound event detection based on ensemble of semi-supervised learning methods"
date: 2019-07-17 08:55:51
categories: arXiv_SD
tags: arXiv_SD Regularization CNN RNN Classification Prediction Detection
author: Ziqiang Shi, Liu Liu, Huibin Lin, Rujie Liu, Anyan Shi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a method called HODGEPODGE\footnotemark[1] for large-scale detection of sound events using weakly labeled, synthetic, and unlabeled data proposed in the Detection and Classification of Acoustic Scenes and Events (DCASE) 2019 challenge Task 4: Sound event detection in domestic environments. To perform this task, we adopted the convolutional recurrent neural networks (CRNN) as our backbone network. In order to deal with a small amount of tagged data and a large amounts of unlabeled in-domain data, we aim to focus primarily on how to apply semi-supervise learning methods efficiently to make full use of limited data. Three semi-supervised learning principles have been used in our system, including: 1) Consistency regularization applies data augmentation; 2) MixUp regularizer requiring that the predictions for a interpolation of two inputs is close to the interpolation of the prediction for each individual input; 3) MixUp regularization applies to interpolation between data augmentations. We also tried an ensemble of various models, which are trained by using different semi-supervised learning principles. Our proposed approach significantly improved the performance of the baseline, achieving the event-based f-measure of 42.0\% compared to 25.8\% event-based f-measure of the baseline in the provided official evaluation dataset. Our submissions ranked third among 18 teams in the task 4.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07398](http://arxiv.org/abs/1907.07398)

##### PDF
[http://arxiv.org/pdf/1907.07398](http://arxiv.org/pdf/1907.07398)

