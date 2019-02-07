---
layout: post
title: "CLEAR: A Consistent Lifting, Embedding, and Alignment Rectification Algorithm for Multi-Agent Data Association"
date: 2019-02-06 16:12:57
categories: arXiv_CV
tags: arXiv_CV Tracking Embedding Object_Tracking SLAM
author: Kaveh Fathian, Kasra Khosoussi, Parker Lusk, Yulun Tian, Jonathan P. How
mathjax: true
---

* content
{:toc}

##### Abstract
A fundamental challenge in many robotics applications is to correctly synchronize and fuse observations across a team of sensors or agents. Instead of solely relying on pairwise matches among observations, multi-way matching methods leverage the notion of cycle consistency to (i) provide a natural correction mechanism for removing noise and outliers from pairwise matches; (ii) construct an efficient and low-rank representation of the data via merging the redundant observations. To solve this computationally challenging problem, state-of-the-art techniques resort to relaxation and rounding techniques that can potentially result in a solution that violates the cycle consistency principle. Hence, losing the aforementioned benefits. In this work, we present the CLEAR algorithm to address this issue by generating solutions that are, by construction, cycle consistent. Through a novel spectral graph clustering approach, CLEAR fuses the techniques in the multi-way matching and the spectral clustering literature and provides consistent solutions, even in challenging high-noise regimes. Our resulting general framework can provide significant improvement in the accuracy and efficiency of existing distributed multi-agent learning, collaborative SLAM, and multiobject tracking pipelines, which traditionally use pairwise (but potentially inconsistent) correspondences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02256](http://arxiv.org/abs/1902.02256)

##### PDF
[http://arxiv.org/pdf/1902.02256](http://arxiv.org/pdf/1902.02256)

