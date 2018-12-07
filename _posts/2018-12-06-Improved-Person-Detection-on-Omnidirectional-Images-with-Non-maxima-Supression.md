---
layout: post
title: "Improved Person Detection on Omnidirectional Images with Non-maxima Supression"
date: 2018-12-06 12:50:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Roman Seidel, Andr&#xe9; Apitzsch, Gangolf Hirtz
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a person detector on omnidirectional images, an accurate method to generate minimal enclosing rectangles of persons. The basic idea is to adapt the qualitative detection performance of a convolutional neural network based method, namely YOLOv2 to fish-eye images. The design of our approach picks up the idea of a state-of-the-art object detector and highly overlapping areas of images with their regions of interests. This overlap reduces the number of false negatives. Based on the raw bounding boxes of the detector we fine-tuned overlapping bounding boxes by three approaches: the non-maximum suppression, the soft non-maximum suppression and the soft non-maximum suppression with Gaussian smoothing. The evaluation was done on the PIROPO database and an own annotated Flat dataset, supplemented with bounding boxes on omnidirectional images. We achieve an average precision of 64.4 % with YOLOv2 for the class person on PIROPO and 77.6 % on Flat. For this purpose we fine-tuned the soft non-maximum suppression with Gaussian smoothing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08503](http://arxiv.org/abs/1805.08503)

##### PDF
[http://arxiv.org/pdf/1805.08503](http://arxiv.org/pdf/1805.08503)

