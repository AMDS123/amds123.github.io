---
layout: post
title: "Person Re-identification with Metric Learning using Privileged Information"
date: 2019-04-10 05:01:28
categories: arXiv_CV
tags: arXiv_CV Re-identification Knowledge Person_Re-identification Optimization
author: Xun Yang, Meng Wang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the promising progress made in recent years, person re-identification remains a challenging task due to complex variations in human appearances from different camera views. This paper presents a logistic discriminant metric learning method for this challenging problem. Different with most existing metric learning algorithms, it exploits both original data and auxiliary data during training, which is motivated by the new machine learning paradigm - Learning Using Privileged Information. Such privileged information is a kind of auxiliary knowledge which is only available during training. Our goal is to learn an optimal distance function by constructing a locally adaptive decision rule with the help of privileged information. We jointly learn two distance metrics by minimizing the empirical loss penalizing the difference between the distance in the original space and that in the privileged space. In our setting, the distance in the privileged space functions as a local decision threshold, which guides the decision making in the original space like a teacher. The metric learned from the original space is used to compute the distance between a probe image and a gallery image during testing. In addition, we extend the proposed approach to a multi-view setting which is able to explore the complementation of multiple feature representations. In the multi-view setting, multiple metrics corresponding to different original features are jointly learned, guided by the same privileged information. Besides, an effective iterative optimization scheme is introduced to simultaneously optimize the metrics and the assigned metric weights. Experiment results on several widely-used datasets demonstrate that the proposed approach is superior to global decision threshold based methods and outperforms most state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05005](http://arxiv.org/abs/1904.05005)

##### PDF
[http://arxiv.org/pdf/1904.05005](http://arxiv.org/pdf/1904.05005)

