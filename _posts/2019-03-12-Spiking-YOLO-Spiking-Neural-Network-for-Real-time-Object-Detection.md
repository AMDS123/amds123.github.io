---
layout: post
title: "Spiking-YOLO: Spiking Neural Network for Real-time Object Detection"
date: 2019-03-12 08:34:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection
author: Seijoon Kim, Seongsik Park, Byunggook Na, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past decade, deep neural networks (DNNs) have become a de-facto standard for solving machine learning problems. As we try to solve more advanced problems, growing demand for computing and power resources are inevitable, nearly impossible to employ DNNs on embedded systems, where available resources are limited. Given these circumstances, spiking neural networks (SNNs) are attracting widespread interest as the third generation of neural network, due to event-driven and low-powered nature. However, SNNs come at the cost of significant performance degradation largely due to complex dynamics of SNN neurons and non-differential spike operation. Thus, its application has been limited to relatively simple tasks such as image classification. In this paper, we investigate the performance degradation of SNNs in the much more challenging task of object detection. From our in-depth analysis, we introduce two novel methods to overcome a significant performance gap: channel-wise normalization and signed neuron with imbalanced threshold. Consequently, we present a spiked-based real-time object detection model, called Spiking-YOLO that provides near-lossless information transmission in a shorter period of time for deep SNN. Our experiments show that the Spiking-YOLO is able to achieve comparable results up to 97% of the original YOLO on a non-trivial dataset, PASCAL VOC.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06530](http://arxiv.org/abs/1903.06530)

##### PDF
[http://arxiv.org/pdf/1903.06530](http://arxiv.org/pdf/1903.06530)

