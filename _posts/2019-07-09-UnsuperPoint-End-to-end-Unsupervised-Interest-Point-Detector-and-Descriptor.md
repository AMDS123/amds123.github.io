---
layout: post
title: "UnsuperPoint: End-to-end Unsupervised Interest Point Detector and Descriptor"
date: 2019-07-09 06:50:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Prediction Detection
author: Peter Hviid Christiansen, Mikkel Fly Kragh, Yury Brodskiy, Henrik Karstoft
mathjax: true
---

* content
{:toc}

##### Abstract
It is hard to create consistent ground truth data for interest points in natural images, since interest points are hard to define clearly and consistently for a human annotator. This makes interest point detectors non-trivial to build. In this work, we introduce an unsupervised deep learning-based interest point detector and descriptor. Using a self-supervised approach, we utilize a siamese network and a novel loss function that enables interest point scores and positions to be learned automatically. The resulting interest point detector and descriptor is UnsuperPoint. We use regression of point positions to 1) make UnsuperPoint end-to-end trainable and 2) to incorporate non-maximum suppression in the model. Unlike most trainable detectors, it requires no generation of pseudo ground truth points, no structure-from-motion-generated representations and the model is learned from only one round of training. Furthermore, we introduce a novel loss function to regularize network predictions to be uniformly distributed. UnsuperPoint runs in real-time with 323 frames per second (fps) at a resolution of $224\times320$ and 90 fps at $480\times640$. It is comparable or better than state-of-the-art performance when measured for speed, repeatability, localization, matching score and homography estimation on the HPatch dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04011](http://arxiv.org/abs/1907.04011)

##### PDF
[http://arxiv.org/pdf/1907.04011](http://arxiv.org/pdf/1907.04011)

