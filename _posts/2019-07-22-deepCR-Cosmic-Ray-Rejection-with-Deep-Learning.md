---
layout: post
title: "deepCR: Cosmic Ray Rejection with Deep Learning"
date: 2019-07-22 18:02:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Deep_Learning Prediction Detection
author: Keming Zhang, Joshua S. Bloom
mathjax: true
---

* content
{:toc}

##### Abstract
Cosmic ray (CR) identification and removal are critical components of imaging and spectroscopic reduction pipelines involving solid-state detectors. We present deepCR, a deep learning based framework for cosmic ray (CR) identification and subsequent image inpainting based on the predicted CR mask. To demonstrate the effectiveness of our framework, we have trained and evaluated models on Hubble Space Telescope ACS/WFC images of sparse extragalactic fields, globular clusters, and resolved galaxies. We demonstrate that at a reasonable false positive rate of 0.5%, deepCR achieves close to 100% detection rates in both extragalactic and globular cluster fields, and 91% in resolved galaxy fields, which is a significant improvement over current state-of-the-art method, LACosmic. Compared to a well-threaded CPU implementation of LACosmic, deepCR mask predictions runs up to 6.5 times faster on CPU and 90 times faster on GPU. For image inpainting, mean squared error of deepDR predictions are 20 times lower in globular cluster fields, 5 times lower in resolved galaxy fields, and 2.5 times lower in extragalactic fields, compared to the best performing non-neural technique. We present our framework and trained models as an open-source Python project, with a simple-to-use API.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09500](http://arxiv.org/abs/1907.09500)

##### PDF
[http://arxiv.org/pdf/1907.09500](http://arxiv.org/pdf/1907.09500)

