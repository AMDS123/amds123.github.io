---
layout: post
title: "Interactive Image Segmentation using Label Propagation through Complex Networks"
date: 2019-01-09 01:22:23
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Fabricio Aparecido Breve
mathjax: true
---

* content
{:toc}

##### Abstract
Interactive image segmentation is a topic of many studies in image processing. In a conventional approach, a user marks some pixels of the object(s) of interest and background, and an algorithm propagates these labels to the rest of the image. This paper presents a new graph-based method for interactive segmentation with two stages. In the first stage, nodes representing pixels are connected to their $k$-nearest neighbors to build a complex network with the small-world property to propagate the labels quickly. In the second stage, a regular network in a grid format is used to refine the segmentation on the object borders. Despite its simplicity, the proposed method can perform the task with high accuracy. Computer simulations are performed using some real-world images to show its effectiveness in both two-classes and multi-classes problems. It is also applied to all the images from the Microsoft GrabCut dataset for comparison, and the segmentation accuracy is comparable to those achieved by some state-of-the-art methods, while it is faster than them. In particular, it outperforms some recent approaches when the user input is composed only by a few "scribbles" draw over the objects. Its computational complexity is only linear on the image size at the best-case scenario and linearithmic in the worst case.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02573](http://arxiv.org/abs/1901.02573)

##### PDF
[http://arxiv.org/pdf/1901.02573](http://arxiv.org/pdf/1901.02573)

