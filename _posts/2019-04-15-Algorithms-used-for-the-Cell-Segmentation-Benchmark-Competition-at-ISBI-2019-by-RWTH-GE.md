---
layout: post
title: "Algorithms used for the Cell Segmentation Benchmark Competition at ISBI 2019 by RWTH-GE"
date: 2019-04-15 07:45:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN Detection
author: Dennis Eschweiler, Johannes Stegmaier
mathjax: true
---

* content
{:toc}

##### Abstract
The presented algorithms for segmentation and tracking follow a 3-step approach where we detect, track and finally segment nuclei. In the preprocessing phase, we detect centroids of the cell nuclei using a convolutional neural network (CNN) for the 2D images and a Laplacian-of-Gaussian Scale Space Maximum Projection approach for the 3D data sets. Tracking was performed in a backwards fashion on the predicted seed points, i.e., starting at the last frame and sequentially connecting corresponding objects until the first frame was reached. Correspondences were identified by propagating detections of a frame t to its preceding frame t-1 and by combining redundant detections using a hierarchical clustering approach. The tracked centroids were then used as input to variants of the seeded watershed algorithm to obtain the final segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06890](http://arxiv.org/abs/1904.06890)

##### PDF
[http://arxiv.org/pdf/1904.06890](http://arxiv.org/pdf/1904.06890)

