---
layout: post
title: "Two-Stream Region Convolutional 3D Network for Temporal Activity Detection"
date: 2019-06-05 02:48:37
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Huijuan Xu, Abir Das, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of temporal activity detection in continuous, untrimmed video streams. This is a difficult task that requires extracting meaningful spatio-temporal features to capture activities, accurately localizing the start and end times of each activity. We introduce a new model, Region Convolutional 3D Network (R-C3D), which encodes the video streams using a three-dimensional fully convolutional network, then generates candidate temporal regions containing activities and finally classifies selected regions into specific activities. Computation is saved due to the sharing of convolutional features between the proposal and the classification pipelines. We further improve the detection performance by efficiently integrating an optical flow based motion stream with the original RGB stream. The two-stream network is jointly optimized by fusing the flow and RGB feature maps at different levels. Additionally, the training stage incorporates an online hard example mining strategy to address the extreme foreground-background imbalance typically observed in any detection pipeline. Instead of heuristically sampling the candidate segments for the final activity classification stage, we rank them according to their performance and only select the worst performers to update the model. This improves the model without heavy hyper-parameter tuning. Extensive experiments on three benchmark datasets are carried out to show superior performance over existing temporal activity detection methods. Our model achieves state-of-the-art results on the THUMOS'14 and Charades datasets. We further demonstrate that our model is a general temporal activity detection framework that does not rely on assumptions about particular dataset properties by evaluating our approach on the ActivityNet dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02182](http://arxiv.org/abs/1906.02182)

##### PDF
[http://arxiv.org/pdf/1906.02182](http://arxiv.org/pdf/1906.02182)

