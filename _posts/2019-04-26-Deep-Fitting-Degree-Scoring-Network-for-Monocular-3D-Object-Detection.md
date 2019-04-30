---
layout: post
title: "Deep Fitting Degree Scoring Network for Monocular 3D Object Detection"
date: 2019-04-26 09:40:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Lijie Liu, Jiwen Lu, Chunjing Xu, Qi Tian, Jie Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to learn a deep fitting degree scoring network for monocular 3D object detection, which aims to score fitting degree between proposals and object conclusively. Different from most existing monocular frameworks which use tight constraint to get 3D location, our approach achieves high-precision localization through measuring the visual fitting degree between the projected 3D proposals and the object. We first regress the dimension and orientation of the object using an anchor-based method so that a suitable 3D proposal can be constructed. We propose FQNet, which can infer the 3D IoU between the 3D proposals and the object solely based on 2D cues. Therefore, during the detection process, we sample a large number of candidates in the 3D space and project these 3D bounding boxes on 2D image individually. The best candidate can be picked out by simply exploring the spatial overlap between proposals and the object, in the form of the output 3D IoU score of FQNet. Experiments on the KITTI dataset demonstrate the effectiveness of our framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12681](http://arxiv.org/abs/1904.12681)

##### PDF
[http://arxiv.org/pdf/1904.12681](http://arxiv.org/pdf/1904.12681)

