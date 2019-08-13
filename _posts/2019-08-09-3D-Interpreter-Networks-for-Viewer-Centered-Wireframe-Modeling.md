---
layout: post
title: "3D Interpreter Networks for Viewer-Centered Wireframe Modeling"
date: 2019-08-09 23:14:56
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge
author: Jiajun Wu, Tianfan Xue, Joseph J. Lim, Yuandong Tian, Joshua B. Tenenbaum, Antonio Torralba, William T. Freeman
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding 3D object structure from a single image is an important but challenging task in computer vision, mostly due to the lack of 3D object annotations to real images. Previous research tackled this problem by either searching for a 3D shape that best explains 2D annotations, or training purely on synthetic data with ground truth 3D information. In this work, we propose 3D INterpreter Networks (3D-INN), an end-to-end trainable framework that sequentially estimates 2D keypoint heatmaps and 3D object skeletons and poses. Our system learns from both 2D-annotated real images and synthetic 3D data. This is made possible mainly by two technical innovations. First, heatmaps of 2D keypoints serve as an intermediate representation to connect real and synthetic data. 3D-INN is trained on real images to estimate 2D keypoint heatmaps from an input image; it then predicts 3D object structure from heatmaps using knowledge learned from synthetic 3D shapes. By doing so, 3D-INN benefits from the variation and abundance of synthetic 3D objects, without suffering from the domain difference between real and synthesized images, often due to imperfect rendering. Second, we propose a Projection Layer, mapping estimated 3D structure back to 2D. During training, it ensures 3D-INN to predict 3D structure whose projection is consistent with the 2D annotations to real images. Experiments show that the proposed system performs well on both 2D keypoint estimation and 3D structure recovery. We also demonstrate that the recovered 3D information has wide vision applications, such as image retrieval.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.00782](http://arxiv.org/abs/1804.00782)

##### PDF
[http://arxiv.org/pdf/1804.00782](http://arxiv.org/pdf/1804.00782)

