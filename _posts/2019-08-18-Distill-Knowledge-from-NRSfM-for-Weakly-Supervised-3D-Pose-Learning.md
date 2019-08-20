---
layout: post
title: "Distill Knowledge from NRSfM for Weakly Supervised 3D Pose Learning"
date: 2019-08-18 04:48:49
categories: arXiv_CV
tags: arXiv_CV Knowledge Weakly_Supervised Pose_Estimation Prediction
author: Chaoyang Wang, Chen Kong, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to learn a 3D pose estimator by distilling knowledge from Non-Rigid Structure from Motion (NRSfM). Our method uses solely 2D landmark annotations. No 3D data, multi-view/temporal footage, or object specific prior is required. This alleviates the data bottleneck, which is one of the major concern for supervised methods. The challenge for using NRSfM as teacher is that they often make poor depth reconstruction when the 2D projections have strong ambiguity. Directly using those wrong depth as hard target would negatively impact the student. Instead, we propose a novel loss that ties depth prediction to the cost function used in NRSfM. This gives the student pose estimator freedom to reduce depth error by associating with image features. Validated on H3.6M dataset, our learned 3D pose estimation network achieves more accurate reconstruction compared to NRSfM methods. It also outperforms other weakly supervised methods, in spite of using significantly less supervision.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06377](http://arxiv.org/abs/1908.06377)

##### PDF
[http://arxiv.org/pdf/1908.06377](http://arxiv.org/pdf/1908.06377)

