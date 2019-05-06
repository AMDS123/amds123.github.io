---
layout: post
title: "LocNet: Improving Localization Accuracy for Object Detection"
date: 2016-04-07 15:09:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Inference Detection
author: Spyros Gidaris, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel object localization methodology with the purpose of boosting the localization accuracy of state-of-the-art object detection systems. Our model, given a search region, aims at returning the bounding box of an object of interest inside this region. To accomplish its goal, it relies on assigning conditional probabilities to each row and column of this region, where these probabilities provide useful information regarding the location of the boundaries of the object inside the search region and allow the accurate inference of the object bounding box under a simple probabilistic framework. For implementing our localization model, we make use of a convolutional neural network architecture that is properly adapted for this task, called LocNet. We show experimentally that LocNet achieves a very significant improvement on the mAP for high IoU thresholds on PASCAL VOC2007 test set and that it can be very easily coupled with recent state-of-the-art object detection systems, helping them to boost their performance. Finally, we demonstrate that our detection approach can achieve high detection accuracy even when it is given as input a set of sliding windows, thus proving that it is independent of box proposal methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1511.07763](https://arxiv.org/abs/1511.07763)

##### PDF
[https://arxiv.org/pdf/1511.07763](https://arxiv.org/pdf/1511.07763)

