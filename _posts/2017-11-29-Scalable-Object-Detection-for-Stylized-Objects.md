---
layout: post
title: "Scalable Object Detection for Stylized Objects"
date: 2017-11-29 10:04:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Recognition
author: Aayush Garg, Thilo Will, William Darling, Willi Richert, Clemens Marschner
mathjax: true
---

* content
{:toc}

##### Abstract
Following recent breakthroughs in convolutional neural networks and monolithic model architectures, state-of-the-art object detection models can reliably and accurately scale into the realm of up to thousands of classes. Things quickly break down, however, when scaling into the tens of thousands, or, eventually, to millions or billions of unique objects. Further, bounding box-trained end-to-end models require extensive training data. Even though - with some tricks using hierarchies - one can sometimes scale up to thousands of classes, the labor requirements for clean image annotations quickly get out of control. In this paper, we present a two-layer object detection method for brand logos and other stylized objects for which prototypical images exist. It can scale to large numbers of unique classes. Our first layer is a CNN from the Single Shot Multibox Detector family of models that learns to propose regions where some stylized object is likely to appear. The contents of a proposed bounding box is then run against an image index that is targeted for the retrieval task at hand. The proposed architecture scales to a large number of object classes, allows to continously add new classes without retraining, and exhibits state-of-the-art quality on a stylized object detection task such as logo recognition.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.09822](https://arxiv.org/abs/1711.09822)

##### PDF
[https://arxiv.org/pdf/1711.09822](https://arxiv.org/pdf/1711.09822)

