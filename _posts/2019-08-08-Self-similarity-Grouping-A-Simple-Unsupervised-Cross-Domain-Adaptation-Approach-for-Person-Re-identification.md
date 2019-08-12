---
layout: post
title: "Self-similarity Grouping: A Simple Unsupervised Cross Domain Adaptation Approach for Person Re-identification"
date: 2019-08-08 21:34:49
categories: arXiv_AI
tags: arXiv_AI Re-identification Person_Re-identification
author: Yang Fu, Yunchao Wei, Guanshuo Wang, Yuqian Zhou, Honghui Shi, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation in person re-identification (re-ID) has always been a challenging task. In this work, we explore how to harness the natural similar characteristics existing in the samples from the target domain for learning to conduct person re-ID in an unsupervised manner. Concretely, we propose a Self-similarity Grouping (SSG) approach, which exploits the potential similarity (from global body to local parts) of unlabeled samples to automatically build multiple clusters from different views. These independent clusters are then assigned with labels, which serve as the pseudo identities to supervise the training process. We repeatedly and alternatively conduct such a grouping and training process until the model is stable. Despite the apparent simplify, our SSG outperforms the state-of-the-arts by more than 4.6% (DukeMTMC to Market1501) and 4.4% (Market1501 to DukeMTMC) in mAP, respectively. Upon our SSG, we further introduce a clustering-guided semisupervised approach named SSG ++ to conduct the one-shot domain adaption in an open set setting (i.e. the number of independent identities from the target domain is unknown). Without spending much effort on labeling, our SSG ++ can further promote the mAP upon SSG by 10.7% and 6.9%, respectively. Our Code is available at: https://github.com/OasisYang/SSG .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10144](http://arxiv.org/abs/1811.10144)

##### PDF
[http://arxiv.org/pdf/1811.10144](http://arxiv.org/pdf/1811.10144)

