---
layout: post
title: "Mask Propagation Network for Video Object Segmentation"
date: 2018-10-24 10:59:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Jia Sun, Dongdong Yu, Yinghong Li, Changhu Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a mask propagation network to treat the video segmentation problem as a concept of the guided instance segmentation. Similar to most MaskTrack based video segmentation methods, our method takes the mask probability map of previous frame and the appearance of current frame as inputs, and predicts the mask probability map for the current frame. Specifically, we adopt the Xception backbone based DeepLab v3+ model as the probability map predictor in our prediction pipeline. Besides, instead of the full image and the original mask probability, our network takes the region of interest of the instance, and the new mask probability which warped by the optical flow between the previous and current frames as the inputs. We also ensemble the modified One-Shot Video Segmentation Network to make the final predictions in order to retrieve and segment the missing instance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10289](http://arxiv.org/abs/1810.10289)

##### PDF
[http://arxiv.org/pdf/1810.10289](http://arxiv.org/pdf/1810.10289)

