---
layout: post
title: "Learning Local Feature Descriptor with Motion Attribute for Vision-based Localization"
date: 2019-08-03 14:05:09
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Yafei Song, Di Zhu, Jia Li, Yonghong Tian, Mingyang Li
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, camera-based localization has been widely used for robotic applications, and most proposed algorithms rely on local features extracted from recorded images. For better performance, the features used for open-loop localization are required to be short-term globally static, and the ones used for re-localization or loop closure detection need to be long-term static. Therefore, the motion attribute of a local feature point could be exploited to improve localization performance, e.g., the feature points extracted from moving persons or vehicles can be excluded from these systems due to their unsteadiness. In this paper, we design a fully convolutional network (FCN), named MD-Net, to perform motion attribute estimation and feature description simultaneously. MD-Net has a shared backbone network to extract features from the input image and two network branches to complete each sub-task. With MD-Net, we can obtain the motion attribute while avoiding increasing much more computation. Experimental results demonstrate that the proposed method can learn distinct local feature descriptor along with motion attribute only using an FCN, by outperforming competing methods by a wide margin. We also show that the proposed algorithm can be integrated into a vision-based localization algorithm to improve estimation accuracy significantly.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01180](http://arxiv.org/abs/1908.01180)

##### PDF
[http://arxiv.org/pdf/1908.01180](http://arxiv.org/pdf/1908.01180)

