---
layout: post
title: "Self-Supervised Flow Estimation using Geometric Regularization with Applications to Camera Image and Grid Map Sequences"
date: 2019-04-17 12:22:03
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking CNN Quantitative
author: Sascha Wirges, Johannes Gr&#xe4;ter, Qiuhao Zhang, Christoph Stiller
mathjax: true
---

* content
{:toc}

##### Abstract
We present a self-supervised approach to estimate flow in camera image and top-view grid map sequences using fully convolutional neural networks in the domain of automated driving. We extend existing approaches for self-supervised optical flow estimation by adding a regularizer expressing motion consistency assuming a static environment. However, as this assumption is violated for other moving traffic participants we also estimate a mask to scale this regularization. Adding a regularization towards motion consistency improves convergence and flow estimation accuracy. Furthermore, we scale the errors due to spatial flow inconsistency by a mask that we derive from the motion mask. This improves accuracy in regions where the flow drastically changes due to a better separation between static and dynamic environment. We apply our approach to optical flow estimation from camera image sequences, validate on odometry estimation and suggest a method to iteratively increase optical flow estimation accuracy using the generated motion masks. Finally, we provide quantitative and qualitative results based on the KITTI odometry and tracking benchmark for scene flow estimation based on grid map sequences. We show that we can improve accuracy and convergence when applying motion and spatial consistency regularization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12599](http://arxiv.org/abs/1904.12599)

##### PDF
[http://arxiv.org/pdf/1904.12599](http://arxiv.org/pdf/1904.12599)

