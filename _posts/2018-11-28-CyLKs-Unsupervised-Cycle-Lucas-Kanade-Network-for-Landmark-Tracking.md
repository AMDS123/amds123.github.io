---
layout: post
title: "CyLKs: Unsupervised Cycle Lucas-Kanade Network for Landmark Tracking"
date: 2018-11-28 00:41:29
categories: arXiv_CV
tags: arXiv_CV Tracking CNN
author: Xinshuo Weng, Wentao Han
mathjax: true
---

* content
{:toc}

##### Abstract
Across a majority of modern learning-based tracking systems, expensive annotations are needed to achieve state-of-the-art performance. In contrast, the Lucas-Kanade (LK) algorithm works well without any annotation. However, LK has a strong assumption of photometric (brightness) consistency on image intensity and is easy to drift because of large motion, occlusion, and aperture problem. To relax the assumption and alleviate the drift problem, we propose CyLKs, a data-driven way of training Lucas-Kanade in an unsupervised manner. CyLKs learns a feature transformation through CNNs, transforming the input images to a feature space which is especially favorable to LK tracking. During training, we perform differentiable Lucas-Kanade forward and backward on the convolutional feature maps, and then minimize the re-projection error. During testing, we perform the LK tracking on the learned features. We apply our model to the task of landmark tracking and perform experiments on datasets of THUMOS, 300VW, and Mugsy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11325](http://arxiv.org/abs/1811.11325)

##### PDF
[http://arxiv.org/pdf/1811.11325](http://arxiv.org/pdf/1811.11325)

