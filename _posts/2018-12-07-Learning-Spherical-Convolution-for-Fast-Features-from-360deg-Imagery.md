---
layout: post
title: "Learning Spherical Convolution for Fast Features from 360{deg} Imagery"
date: 2018-12-07 17:34:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Yu-Chuan Su, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
While 360{\deg} cameras offer tremendous new possibilities in vision, graphics, and augmented reality, the spherical images they produce make core feature extraction non-trivial. Convolutional neural networks (CNNs) trained on images from perspective cameras yield "flat" filters, yet 360{\deg} images cannot be projected to a single plane without significant distortion. A naive solution that repeatedly projects the viewing sphere to all tangent planes is accurate, but much too computationally intensive for real problems. We propose to learn a spherical convolutional network that translates a planar CNN to process 360{\deg} imagery directly in its equirectangular projection. Our approach learns to reproduce the flat filter outputs on 360{\deg} data, sensitive to the varying distortion effects across the viewing sphere. The key benefits are 1) efficient feature extraction for 360{\deg} images and video, and 2) the ability to leverage powerful pre-trained networks researchers have carefully honed (together with massive labeled image training sets) for perspective images. We validate our approach compared to several alternative methods in terms of both raw CNN output accuracy as well as applying a state-of-the-art "flat" object detector to 360{\deg} data. Our method yields the most accurate results while saving orders of magnitude in computation versus the existing exact reprojection solution.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.00919](http://arxiv.org/abs/1708.00919)

##### PDF
[http://arxiv.org/pdf/1708.00919](http://arxiv.org/pdf/1708.00919)

