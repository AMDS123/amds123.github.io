---
layout: post
title: "Fully-automatic segmentation of kidneys in clinical ultrasound images using a boundary distance regression network"
date: 2019-01-05 19:44:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning
author: Shi Yin, Zhengqiang Zhang, Hongming Li, Qinmu Peng, Xinge You, Susan L. Furth, Gregory E. Tasian, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
It remains challenging to automatically segment kidneys in clinical ultrasound images due to the kidneys' varied shapes and image intensity distributions, although semi-automatic methods have achieved promising performance. In this study, we developed a novel boundary distance regression deep neural network to segment the kidneys, informed by the fact that the kidney boundaries are relatively consistent across images in terms of their appearance. Particularly, we first use deep neural networks pre-trained for classification of natural images to extract high-level image features from ultrasound images, then these feature maps are used as input to learn kidney boundary distance maps using a boundary distance regression network, and finally the predicted boundary distance maps are classified as kidney pixels or non-kidney pixels using a pixel classification network in an end-to-end learning fashion. Experimental results have demonstrated that our method could effectively improve the performance of automatic kidney segmentation, significantly better than deep learning based pixel classification networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01982](http://arxiv.org/abs/1901.01982)

##### PDF
[http://arxiv.org/pdf/1901.01982](http://arxiv.org/pdf/1901.01982)

