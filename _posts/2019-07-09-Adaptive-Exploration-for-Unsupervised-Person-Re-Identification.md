---
layout: post
title: "Adaptive Exploration for Unsupervised Person Re-Identification"
date: 2019-07-09 14:36:08
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Yuhang Ding, Hehe Fan, Mingliang Xu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Due to domain bias, directly deploying a deep person re-identification (re-ID) model trained on one dataset often achieves considerably poor accuracy on another dataset. In this paper, we propose an Adaptive Exploration (AE) method to address the domain-shift problem for re-ID in an unsupervised manner. Specifically, with supervised training on the source dataset, in the target domain, the re-ID model is inducted to 1) maximize distances between all person images and 2) minimize distances between similar person images. In the first case, by treating each person image as an individual class, a non-parametric classifier with a feature memory is exploited to encourage person images to move away from each other. In the second case, according to a similarity threshold, our method adaptively selects neighborhoods in the feature space for each person image. By treating these similar person images as the same class, the non-parametric classifier forces them to stay closer. However, a problem of adaptive selection is that, when an image has too many neighborhoods, it is more likely to attract other images as its neighborhoods. As a result, a minority of images may select a large number of neighborhoods while a majority of images has only a few neighborhoods. To address this issue, we additionally integrate a balance strategy into the adaptive selection. Extensive experiments on large-scale re-ID datasets demonstrate the effectiveness of our method. Our code has been released at https://github.com/dyh127/Adaptive-Exploration-for-Unsupervised-Person-Re-Identification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04194](http://arxiv.org/abs/1907.04194)

##### PDF
[http://arxiv.org/pdf/1907.04194](http://arxiv.org/pdf/1907.04194)

