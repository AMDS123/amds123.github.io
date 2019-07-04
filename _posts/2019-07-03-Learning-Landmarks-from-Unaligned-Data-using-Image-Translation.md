---
layout: post
title: "Learning Landmarks from Unaligned Data using Image Translation"
date: 2019-07-03 17:47:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Detection
author: Tomas Jakab, Ankush Gupta, Hakan Bilen, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a method for learning landmark detectors from unlabelled video frames and unpaired labels. This allows us to learn a detector from a large collection of raw videos given only a few example annotations harvested from existing data or motion capture. We achieve this by formulating the landmark detection task as one of image translation, learning to map an image of the object to an image of its landmarks, represented as a skeleton. The advantage is that this translation problem can then be tackled by CycleGAN. However, we show that a naive application of CycleGAN confounds appearance and pose information, with suboptimal keypoint detection performance. We solve this problem by introducing an analytical and differentiable renderer for the skeleton image so that no appearance information can be leaked in the skeleton. Then, since cycle consistency requires to reconstruct the input image from the skeleton, we supply the appearance information thus removed by conditioning the generator with a second image of the same object (e.g. another frame from a video). Furthermore, while CycleGAN uses two cycle consistency constraints, we show that the second one is detrimental in this application and we discard it, significantly simplifying the model. We show that these modifications improve the quality of the learned detector leading to state-of-the-art unsupervised landmark detection performance in a number of challenging human pose and facial landmark detection benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02055](http://arxiv.org/abs/1907.02055)

##### PDF
[http://arxiv.org/pdf/1907.02055](http://arxiv.org/pdf/1907.02055)

