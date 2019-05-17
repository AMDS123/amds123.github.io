---
layout: post
title: "Remove Cosine Window from Correlation Filter-based Visual Trackers: When and How"
date: 2019-05-16 10:34:57
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking Relation
author: Feng Li, Xiaohe Wu, Wangmeng Zuo, David Zhang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filters (CFs) have been continuously advancing the state-of-the-art tracking performance and have been extensively studied in the recent few years. Most of the existing CF trackers adopt a cosine window to spatially reweight base image to alleviate boundary discontinuity. However, cosine window emphasizes more on the central region of base image and has the risk of contaminating negative training samples during model learning. On the other hand, spatial regularization deployed in many recent CF trackers plays a similar role as cosine window by enforcing spatial penalty on CF coefficients. Therefore, we in this paper investigate the feasibility to remove cosine window from CF trackers with spatial regularization. When simply removing cosine window, CF with spatial regularization still suffers from small degree of boundary discontinuity. To tackle this issue, binary and Gaussian shaped mask functions are further introduced for eliminating boundary discontinuity while reweighting the estimation error of each training sample, and can be incorporated with multiple CF trackers with spatial regularization. In comparison to the counterparts with cosine window, our methods are effective in handling boundary discontinuity and sample contamination, thereby benefiting tracking performance. Extensive experiments on three benchmarks show that our methods perform favorably against the state-of-the-art trackers using either handcrafted or deep CNN features. The code is publicly available at https://github.com/lifeng9472/Removing_cosine_window_from_CF_trackers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06648](http://arxiv.org/abs/1905.06648)

##### PDF
[http://arxiv.org/pdf/1905.06648](http://arxiv.org/pdf/1905.06648)

