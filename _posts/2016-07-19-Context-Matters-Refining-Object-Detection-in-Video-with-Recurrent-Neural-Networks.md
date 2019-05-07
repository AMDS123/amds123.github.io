---
layout: post
title: "Context Matters: Refining Object Detection in Video with Recurrent Neural Networks"
date: 2016-07-19 03:00:35
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Sparse CNN RNN Prediction Detection
author: Subarna Tripathi, Zachary C. Lipton, Serge Belongie, Truong Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Given the vast amounts of video available online, and recent breakthroughs in object detection with static images, object detection in video offers a promising new frontier. However, motion blur and compression artifacts cause substantial frame-level variability, even in videos that appear smooth to the eye. Additionally, video datasets tend to have sparsely annotated frames. We present a new framework for improving object detection in videos that captures temporal context and encourages consistency of predictions. First, we train a pseudo-labeler, that is, a domain-adapted convolutional neural network for object detection. The pseudo-labeler is first trained individually on the subset of labeled frames, and then subsequently applied to all frames. Then we train a recurrent neural network that takes as input sequences of pseudo-labeled frames and optimizes an objective that encourages both accuracy on the target frame and consistency across consecutive frames. The approach incorporates strong supervision of target frames, weak-supervision on context frames, and regularization via a smoothness penalty. Our approach achieves mean Average Precision (mAP) of 68.73, an improvement of 7.1 over the strongest image-based baselines for the Youtube-Video Objects dataset. Our experiments demonstrate that neighboring frames can provide valuable information, even absent labels.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1607.04648](https://arxiv.org/abs/1607.04648)

##### PDF
[https://arxiv.org/pdf/1607.04648](https://arxiv.org/pdf/1607.04648)

