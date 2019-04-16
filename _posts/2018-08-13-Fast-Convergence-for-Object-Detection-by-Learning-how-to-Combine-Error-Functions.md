---
layout: post
title: "Fast Convergence for Object Detection by Learning how to Combine Error Functions"
date: 2018-08-13 22:20:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Benjamin Schnieders, Karl Tuyls
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce an innovative method to improve the convergence speed and accuracy of object detection neural networks. Our approach, CONVERGE-FAST-AUXNET, is based on employing multiple, dependent loss metrics and weighting them optimally using an on-line trained auxiliary network. Experiments are performed in the well-known RoboCup@Work challenge environment. A fully convolutional segmentation network is trained on detecting objects' pickup points. We empirically obtain an approximate measure for the rate of success of a robotic pickup operation based on the accuracy of the object detection network. Our experiments show that adding an optimally weighted Euclidean distance loss to a network trained on the commonly used Intersection over Union (IoU) metric reduces the convergence time by 42.48%. The estimated pickup rate is improved by 39.90%. Compared to state-of-the-art task weighting methods, the improvement is 24.5% in convergence, and 15.8% on the estimated pickup rate.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.04480](https://arxiv.org/abs/1808.04480)

##### PDF
[https://arxiv.org/pdf/1808.04480](https://arxiv.org/pdf/1808.04480)

