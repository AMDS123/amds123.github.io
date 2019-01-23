---
layout: post
title: "Unsupervised Automated Event Detection using an Iterative Clustering based Segmentation Approach"
date: 2019-01-22 09:24:58
categories: arXiv_AI
tags: arXiv_AI Segmentation Detection
author: Deepak K. Gupta, Rohit K. Shrivastava, Suhas Phadke, Jeroen Goudswaard
mathjax: true
---

* content
{:toc}

##### Abstract
A class of vision problems, less commonly studied, consists of detecting objects in imagery obtained from physics-based experiments. These objects can span in 4D (x, y, z, t) and are visible as disturbances (caused due to physical phenomena) in the image with background distribution being approximately uniform. Such objects, occasionally referred to as `events', can be considered as high energy blobs in the image. Unlike the images analyzed in conventional vision problems, very limited features are associated with such events, and their shape, size and count can vary significantly. This poses a challenge on the use of pre-trained models obtained from supervised approaches. 
 In this paper, we propose an unsupervised approach involving iterative clustering based segmentation (ICS) which can detect target objects (events) in real-time. In this approach, a test image is analyzed over several cycles, and one event is identified per cycle. Each cycle consists of the following steps: (1) image segmentation using a modified k-means clustering method, (2) elimination of empty (with no events) segments based on statistical analysis of each segment, (3) merging segments that overlap (correspond to same event), and (4) selecting the strongest event. These four steps are repeated until all the events have been identified. The ICS approach consists of a few hyper-parameters that have been chosen based on statistical study performed over a set of test images. The applicability of ICS method is demonstrated on several 2D and 3D test examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07222](http://arxiv.org/abs/1901.07222)

##### PDF
[http://arxiv.org/pdf/1901.07222](http://arxiv.org/pdf/1901.07222)

