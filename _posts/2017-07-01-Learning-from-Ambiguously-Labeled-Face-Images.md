---
layout: post
title: "Learning from Ambiguously Labeled Face Images"
date: 2017-07-01 05:35:22
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Caption
author: Ching-Hui Chen, Vishal M. Patel, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a classifier from ambiguously labeled face images is challenging since training images are not always explicitly-labeled. For instance, face images of two persons in a news photo are not explicitly labeled by their names in the caption. We propose a Matrix Completion for Ambiguity Resolution (MCar) method for predicting the actual labels from ambiguously labeled images. This step is followed by learning a standard supervised classifier from the disambiguated labels to classify new images. To prevent the majority labels from dominating the result of MCar, we generalize MCar to a weighted MCar (WMCar) that handles label imbalance. Since WMCar outputs a soft labeling vector of reduced ambiguity for each instance, we can iteratively refine it by feeding it as the input to WMCar. Nevertheless, such an iterative implementation can be affected by the noisy soft labeling vectors, and thus the performance may degrade. Our proposed Iterative Candidate Elimination (ICE) procedure makes the iterative ambiguity resolution possible by gradually eliminating a portion of least likely candidates in ambiguously labeled face. We further extend MCar to incorporate the labeling constraints between instances when such prior knowledge is available. Compared to existing methods, our approach demonstrates improvement on several ambiguously labeled datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.04455](https://arxiv.org/abs/1702.04455)

##### PDF
[https://arxiv.org/pdf/1702.04455](https://arxiv.org/pdf/1702.04455)

