---
layout: post
title: "Unsupervised Learning for Color Constancy"
date: 2019-03-15 14:30:10
categories: arXiv_CV
tags: arXiv_CV
author: Nikola Bani&#x107;, Karlo Ko&#x161;&#x10d;evi&#x107;, Sven Lon&#x10d;ari&#x107;
mathjax: true
---

* content
{:toc}

##### Abstract
Most digital camera pipelines use color constancy methods to reduce the influence of illumination and camera sensor on the colors of scene objects. The highest accuracy of color correction is obtained with learning-based color constancy methods, but they require a significant amount of calibrated training images with known ground-truth illumination. Such calibration is time consuming, preferably done for each sensor individually, and therefore a major bottleneck in acquiring high color constancy accuracy. Statistics-based methods do not require calibrated training images, but they are less accurate. In this paper an unsupervised learning-based method is proposed that learns its parameter values after approximating the unknown ground-truth illumination of the training images, thus avoiding calibration. In terms of accuracy the proposed method outperforms all statistics-based and many learning-based methods. An extension of the method is also proposed, which learns the needed parameters from non-calibrated images taken with one sensor and which can then be successfully applied to images taken with another sensor. This effectively enables inter-camera unsupervised learning for color constancy. Additionally, a new high quality color constancy benchmark dataset with 1707 calibrated images is created, used for testing, and made publicly available. The results are presented and discussed. The source code and the dataset are available at <a href="http://www.fer.unizg.hr/ipg/resources/color_constancy/.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.00436](http://arxiv.org/abs/1712.00436)

##### PDF
[http://arxiv.org/pdf/1712.00436](http://arxiv.org/pdf/1712.00436)

