---
layout: post
title: "Continuous Trade-off Optimization between Fast and Accurate Deep Face Detectors"
date: 2018-11-27 12:16:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Optimization Inference Detection Face_Detection
author: Petru Soviany, Radu Tudor Ionescu
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep neural networks offer better face detection results than shallow or handcrafted models, their complex architectures come with higher computational requirements and slower inference speeds than shallow neural networks. In this context, we study five straightforward approaches to achieve an optimal trade-off between accuracy and speed in face detection. All the approaches are based on separating the test images in two batches, an easy batch that is fed to a faster face detector and a difficult batch that is fed to a more accurate yet slower detector. We conduct experiments on the AFW and the FDDB data sets, using MobileNet-SSD as the fast face detector and S3FD (Single Shot Scale-invariant Face Detector) as the accurate face detector, both models being pre-trained on the WIDER FACE data set. Our experiments show that the proposed difficulty metrics compare favorably to a random split of the images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11582](http://arxiv.org/abs/1811.11582)

##### PDF
[http://arxiv.org/pdf/1811.11582](http://arxiv.org/pdf/1811.11582)

