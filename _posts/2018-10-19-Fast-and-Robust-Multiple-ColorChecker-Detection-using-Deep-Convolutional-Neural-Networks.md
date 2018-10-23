---
layout: post
title: "Fast and Robust Multiple ColorChecker Detection using Deep Convolutional Neural Networks"
date: 2018-10-19 18:39:53
categories: arXiv_CV
tags: arXiv_CV CNN Detection Recognition
author: Pedro D. Marrero Fernandez, Fidel A. Guerrero-Pe&#xf1;a, Tsang Ing Ren, Jorge J. G. Leandro
mathjax: true
---

* content
{:toc}

##### Abstract
ColorCheckers are reference standards that professional photographers and filmmakers use to ensure predictable results under every lighting condition. The objective of this work is to propose a new fast and robust method for automatic ColorChecker detection. The process is divided into two steps: (1) ColorCheckers localization and (2) ColorChecker patches recognition. For the ColorChecker localization, we trained a detection convolutional neural network using synthetic images. The synthetic images are created with the 3D models of the ColorChecker and different background images. The output of the neural networks are the bounding box of each possible ColorChecker candidates in the input image. Each bounding box defines a cropped image which is evaluated by a recognition system, and each image is canonized with regards to color and dimensions. Subsequently, all possible color patches are extracted and grouped with respect to the center's distance. Each group is evaluated as a candidate for a ColorChecker part, and its position in the scene is estimated. Finally, a cost function is applied to evaluate the accuracy of the estimation. The method is tested using real and synthetic images. The proposed method is fast, robust to overlaps and invariant to affine projections. The algorithm also performs well in case of multiple ColorCheckers detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08639](http://arxiv.org/abs/1810.08639)

##### PDF
[http://arxiv.org/pdf/1810.08639](http://arxiv.org/pdf/1810.08639)

