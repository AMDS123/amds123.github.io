---
layout: post
title: "Multiple Hypothesis Tracking Algorithm for Multi-Target Multi-Camera Tracking with Disjoint Views"
date: 2019-01-25 09:01:05
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Kwangjin Yoon, Young-min Song, Moongu Jeon
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, a multiple hypothesis tracking (MHT) algorithm for multi-target multi-camera tracking (MCT) with disjoint views is proposed. Our method forms track-hypothesis trees, and each branch of them represents a multi-camera track of a target that may move within a camera as well as move across cameras. Furthermore, multi-target tracking within a camera is performed simultaneously with the tree formation by manipulating a status of each track hypothesis. Each status represents three different stages of a multi-camera track: tracking, searching, and end-of-track. The tracking status means targets are tracked by a single camera tracker. In the searching status, the disappeared targets are examined if they reappear in other cameras. The end-of-track status does the target exited the camera network due to its lengthy invisibility. These three status assists MHT to form the track-hypothesis trees for multi-camera tracking. Furthermore, they present a gating technique for eliminating of unlikely observation-to-track association. In the experiments, they evaluate the proposed method using two datasets, DukeMTMC and NLPR-MCT, which demonstrates that the proposed method outperforms the state-of-the-art method in terms of improvement of the accuracy. In addition, they show that the proposed method can operate in real-time and online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08787](http://arxiv.org/abs/1901.08787)

##### PDF
[http://arxiv.org/pdf/1901.08787](http://arxiv.org/pdf/1901.08787)

