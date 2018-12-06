---
layout: post
title: "Unsupervised Generation of Optical Flow Datasets from Videos in the Wild"
date: 2018-12-05 12:10:06
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Hoang-An Le, Tushar Nimbhorkar, Thomas Mensink, Sezer Karaoglu, Anil S. Baslamisli, Theo Gevers
mathjax: true
---

* content
{:toc}

##### Abstract
Dense optical flow ground truth of non-rigid motion for real-world images are not available due to the non-intuitive annotation. Aiming at training optical flow deep networks, we present an unsupervised algorithm to generate optical flow ground truth from real-world videos. The algorithm extracts and matches objects of interest from pairs of images in videos to find initial constraints, and applies as-rigid-as-possible deformation over the objects of interest to obtain dense flow fields. The ground truth correctness is enforced by warping the objects in the first frames using the flow fields. We apply the algorithm on the DAVIS dataset to obtain optical flow ground truths for non-rigid movement of real-world objects, using either ground truth or predicted segmentation. We discuss several methods to increase the optical flow variations in the dataset. Extensive experimental results show that training on non-rigid real motion is beneficial compared to training on rigid synthetic data. Moreover, we show that our pipeline generates training data suitable to train successfully FlowNet-S, PWC-Net, and LiteFlowNet deep networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01946](http://arxiv.org/abs/1812.01946)

##### PDF
[http://arxiv.org/pdf/1812.01946](http://arxiv.org/pdf/1812.01946)

