---
layout: post
title: "ELASTIC: Improving CNNs with Instance Specific Scaling Policies"
date: 2018-12-13 05:00:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Huiyu Wang, Aniruddha Kembhavi, Ali Farhadi, Alan Yuille, Mohammad Rastegari
mathjax: true
---

* content
{:toc}

##### Abstract
Scale variation has been a challenge from traditional to modern approaches in computer vision. Most solutions to scale issues have similar theme: a set of intuitive and manually designed policies that are generic and fixed (e.g. SIFT or feature pyramid). We argue that the scale policy should be learned from data. In this paper, we introduce ELASTIC, a simple, efficient and yet very effective approach to learn instance-specific scale policy from data. We formulate the scaling policy as a non-linear function inside the network's structure that (a) is learned from data, (b) is instance specific, (c) does not add extra computation, and (d) can be applied on any network architecture. We applied ELASTIC to several state-of-the-art network architectures and showed consistent improvement without extra (sometimes even lower) computation on ImageNet classification, MSCOCO multi-label classification, and PASCAL VOC semantic segmentation. Our results show major improvement for images with scale challenges e.g. images with several small objects or objects with large scale variations. Our code and models will be publicly available soon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05262](http://arxiv.org/abs/1812.05262)

##### PDF
[http://arxiv.org/pdf/1812.05262](http://arxiv.org/pdf/1812.05262)

