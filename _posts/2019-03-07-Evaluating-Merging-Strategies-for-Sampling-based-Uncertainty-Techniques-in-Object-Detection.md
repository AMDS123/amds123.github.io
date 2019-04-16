---
layout: post
title: "Evaluating Merging Strategies for Sampling-based Uncertainty Techniques in Object Detection"
date: 2019-03-07 00:02:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Classification Detection
author: Dimity Miller, Feras Dayoub, Michael Milford, Niko Sünderhauf
mathjax: true
---

* content
{:toc}

##### Abstract
There has been a recent emergence of sampling-based techniques for estimating epistemic uncertainty in deep neural networks. While these methods can be applied to classification or semantic segmentation tasks by simply averaging samples, this is not the case for object detection, where detection sample bounding boxes must be accurately associated and merged. A weak merging strategy can significantly degrade the performance of the detector and yield an unreliable uncertainty measure. This paper provides the first in-depth investigation of the effect of different association and merging strategies. We compare different combinations of three spatial and two semantic affinity measures with four clustering methods for MC Dropout with a Single Shot Multi-Box Detector. Our results show that the correct choice of affinity-clustering combination can greatly improve the effectiveness of the classification and spatial uncertainty estimation and the resulting object detection performance. We base our evaluation on a new mix of datasets that emulate near open-set conditions (semantically similar unknown classes), distant open-set conditions (semantically dissimilar unknown classes) and the common closed-set conditions (only known classes).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.06006](https://arxiv.org/abs/1809.06006)

##### PDF
[https://arxiv.org/pdf/1809.06006](https://arxiv.org/pdf/1809.06006)

