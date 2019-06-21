---
layout: post
title: "Multi-linear Faster RCNN with ELA for Image Tampering Detection"
date: 2019-06-20 17:37:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Robin Elizabeth Yancey, Norman Matloff, Paul Thompson
mathjax: true
---

* content
{:toc}

##### Abstract
With technological advances leading to an increase in mechanisms for image tampering, fraud detection methods must continue to be upgraded to match their sophistication. One problem with current methods is that they require prior knowledge of the method of forgery in order to determine which features to extract from the image to localize the region of interest. When a machine learning algorithm is used to learn different types of tampering from a large set of various image types, with a large enough database we can easily classify which images are tampered (by training on the entire image feature map for each image). However, we still are left with the question of which features to train on, and how to localize the manipulation. To solve this, object detection networks such as Faster R-CNN, which combine an RPN (Region Proposal Network) with a CNN, have recently been adapted to fraud detection by utilizing their ability to propose bounding boxes for objects of interest to localize the tampering artifacts. By making use of the computational powers of today's GPUs this method also achieves a fast run-time and higher accuracy than the top current methods such as noise analysis, ELA (Error Level Analysis), or CFA (Color Filter Array). In this work, a multi-linear Faster RCNN network will be applied similarly but with the second stream having an input of the ELA JPEG compression level mask. This is shown to provide even higher accuracy by adding training features from the segmented image map to the network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08484](http://arxiv.org/abs/1904.08484)

##### PDF
[http://arxiv.org/pdf/1904.08484](http://arxiv.org/pdf/1904.08484)

