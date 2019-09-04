---
layout: post
title: "Estimation of Absolute Scale in Monocular SLAM Using Synthetic Data"
date: 2019-09-02 13:35:01
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Danila Rukhovich, Daniel Mouritzen, Ralf Kaestner, Martin Rufli, Alexander Velizhev
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of scale estimation in monocular SLAM by estimating absolute distances between camera centers of consecutive image frames. These estimates would improve the overall performance of classical (not deep) SLAM systems and allow metric feature locations to be recovered from a single monocular camera. We propose several network architectures that lead to an improvement of scale estimation accuracy over the state of the art. In addition, we exploit a possibility to train the neural network only with synthetic data derived from a computer graphics simulator. Our key insight is that, using only synthetic training inputs, we can achieve similar scale estimation accuracy as that obtained from real data. This fact indicates that fully annotated simulated data is a viable alternative to existing deep-learning-based SLAM systems trained on real (unlabeled) data. Our experiments with unsupervised domain adaptation also show that the difference in visual appearance between simulated and real data does not affect scale estimation results. Our method operates with low-resolution images (0.03MP), which makes it practical for real-time SLAM applications with a monocular camera.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00713](http://arxiv.org/abs/1909.00713)

##### PDF
[http://arxiv.org/pdf/1909.00713](http://arxiv.org/pdf/1909.00713)

