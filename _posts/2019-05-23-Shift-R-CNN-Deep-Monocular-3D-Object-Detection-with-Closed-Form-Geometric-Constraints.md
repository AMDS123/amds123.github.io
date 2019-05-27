---
layout: post
title: "Shift R-CNN: Deep Monocular 3D Object Detection with Closed-Form Geometric Constraints"
date: 2019-05-23 23:41:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Andretti Naiden, Vlad Paunescu, Gyeongmo Kim, ByeongMoon Jeon, Marius Leordeanu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Shift R-CNN, a hybrid model for monocular 3D object detection, which combines deep learning with the power of geometry. We adapt a Faster R-CNN network for regressing initial 2D and 3D object properties and combine it with a least squares solution for the inverse 2D to 3D geometric mapping problem, using the camera projection matrix. The closed-form solution of the mathematical system, along with the initial output of the adapted Faster R-CNN are then passed through a final ShiftNet network that refines the result using our newly proposed Volume Displacement Loss. Our novel, geometrically constrained deep learning approach to monocular 3D object detection obtains top results on KITTI 3D Object Detection Benchmark, being the best among all monocular methods that do not use any pre-trained network for depth estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09970](http://arxiv.org/abs/1905.09970)

##### PDF
[http://arxiv.org/pdf/1905.09970](http://arxiv.org/pdf/1905.09970)

