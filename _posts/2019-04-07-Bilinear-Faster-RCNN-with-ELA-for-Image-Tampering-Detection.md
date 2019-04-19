---
layout: post
title: "Bilinear Faster RCNN with ELA for Image Tampering Detection"
date: 2019-04-07 19:39:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Robin Elizabeth Yancey
mathjax: true
---

* content
{:toc}

##### Abstract
With technological advances leading to an increase in mechanisms of image tampering, our fraud detection methods must continue to be upgraded to match their sophistication. One problem with current methods is that they require prior knowledge of the method of forgery in order to determine which features to extract from the image to localize the region of interest. When a machine learning algorithm is used to learn different types tampering from a large set of various image types, with a big enough database we can easily classify which images are tampered (by training on the entire image feature map for each image), but we still are left with the question of which features to train on, and how to localize the manipulation. To solve this, object detection networks such as Faster RCNN, which combine an RPN (Region Proposal Network) with a CNN have recently been adapted to fraud detection by utilizing their ability to propose bounding boxes for objects of interest to localize the tampering artifacts. In this work, an existing bilinear Faster RCNN model that was developed will be modified with the second stream having an input of the ELA (Error Level Analysis) JPEG compression level mask.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08484](http://arxiv.org/abs/1904.08484)

##### PDF
[http://arxiv.org/pdf/1904.08484](http://arxiv.org/pdf/1904.08484)

