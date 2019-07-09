---
layout: post
title: "A Novel Teacher-Student Learning Framework For Occluded Person Re-Identification"
date: 2019-07-07 08:52:38
categories: arXiv_CV
tags: arXiv_CV Salient Re-identification Knowledge Person_Re-identification Classification Recognition
author: Jiaxuan Zhuo, Jianhuang Lai, Peijia Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-id) has made great progress in recent years, but occlusion is still a challenging problem which significantly degenerates the identification performance. In this paper, we design a teacher-student learning framework to learn an occlusion-robust model from the full-body person domain to the occluded person domain. Notably, the teacher network only uses large-scale full-body person data to simulate the learning process of occluded person re-id. Based on the teacher network, the student network then trains a better model by using inadequate real-world occluded person data. In order to transfer more knowledge from the teacher network to the student network, we equip the proposed framework with a co-saliency network and a cross-domain simulator. The co-saliency network extracts the backbone features, and two separated collaborative branches are followed by the backbone. One branch is a classification branch for identity recognition and the other is a co-saliency branch for guiding the network to highlight meaningful parts without any manual annotation. The cross-domain simulator generates artificial occlusions on full-body person data under a growing probability so that the teacher network could train a cross-domain model by observing more and more occluded cases. Experiments on four occluded person re-id benchmarks show that our method outperforms other state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03253](http://arxiv.org/abs/1907.03253)

##### PDF
[http://arxiv.org/pdf/1907.03253](http://arxiv.org/pdf/1907.03253)

