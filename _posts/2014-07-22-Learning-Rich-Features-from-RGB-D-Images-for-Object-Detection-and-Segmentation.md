---
layout: post
title: "Learning Rich Features from RGB-D Images for Object Detection and Segmentation"
date: 2014-07-22 05:31:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Embedding CNN Classification Detection
author: Saurabh Gupta, Ross Girshick, Pablo Arbeláez, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we study the problem of object detection for RGB-D images using semantically rich image and depth features. We propose a new geocentric embedding for depth images that encodes height above ground and angle with gravity for each pixel in addition to the horizontal disparity. We demonstrate that this geocentric embedding works better than using raw depth images for learning feature representations with convolutional neural networks. Our final object detection system achieves an average precision of 37.3%, which is a 56% relative improvement over existing methods. We then focus on the task of instance segmentation where we label pixels belonging to object instances found by our detector. For this task, we propose a decision forest approach that classifies pixels in the detection window as foreground or background using a family of unary and binary tests that query shape and geocentric pose features. Finally, we use the output from our object detectors in an existing superpixel classification framework for semantic scene segmentation and achieve a 24% relative improvement over current state-of-the-art for the object categories that we study. We believe advances such as those represented in this paper will facilitate the use of perception in fields like robotics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1407.5736](https://arxiv.org/abs/1407.5736)

##### PDF
[https://arxiv.org/pdf/1407.5736](https://arxiv.org/pdf/1407.5736)

