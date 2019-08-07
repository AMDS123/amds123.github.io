---
layout: post
title: "Attention Control with Metric Learning Alignment for Image Set-based Recognition"
date: 2019-08-05 21:48:05
categories: arXiv_CV
tags: arXiv_CV Attention Face Reinforcement_Learning Detection Relation Recognition Face_Recognition
author: Xiaofeng Liu, Zhenhua Guo, Jane You, B.V.K Vijaya Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the problem of image set-based face verification and identification. Unlike traditional single sample (an image or a video) setting, this situation assumes the availability of a set of heterogeneous collection of orderless images and videos. The samples can be taken at different check points, different identity documents $etc$. The importance of each image is usually considered either equal or based on a quality assessment of that image independent of other images and/or videos in that image set. How to model the relationship of orderless images within a set remains a challenge. We address this problem by formulating it as a Markov Decision Process (MDP) in a latent space. Specifically, we first propose a dependency-aware attention control (DAC) network, which uses actor-critic reinforcement learning for attention decision of each image to exploit the correlations among the unordered images. An off-policy experience replay is introduced to speed up the learning process. Moreover, the DAC is combined with a temporal model for videos using divide and conquer strategies. We also introduce a pose-guided representation (PGR) scheme that can further boost the performance at extreme poses. We propose a parameter-free PGR without the need for training as well as a novel metric learning-based PGR for pose alignment without the need for pose detection in testing stage. Extensive evaluations on IJB-A/B/C, YTF, Celebrity-1000 datasets demonstrate that our method outperforms many state-of-art approaches on the set-based as well as video-based face recognition databases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01872](http://arxiv.org/abs/1908.01872)

##### PDF
[http://arxiv.org/pdf/1908.01872](http://arxiv.org/pdf/1908.01872)

