---
layout: post
title: "Deep Sliding Shapes for Amodal 3D Object Detection in RGB-D Images"
date: 2016-03-09 19:21:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Recognition
author: Shuran Song, Jianxiong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the task of amodal 3D object detection in RGB-D images, which aims to produce a 3D bounding box of an object in metric form at its full extent. We introduce Deep Sliding Shapes, a 3D ConvNet formulation that takes a 3D volumetric scene from a RGB-D image as input and outputs 3D object bounding boxes. In our approach, we propose the first 3D Region Proposal Network (RPN) to learn objectness from geometric shapes and the first joint Object Recognition Network (ORN) to extract geometric features in 3D and color features in 2D. In particular, we handle objects of various sizes by training an amodal RPN at two different scales and an ORN to regress 3D bounding boxes. Experiments show that our algorithm outperforms the state-of-the-art by 13.8 in mAP and is 200x faster than the original Sliding Shapes. All source code and pre-trained models will be available at GitHub.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1511.02300](https://arxiv.org/abs/1511.02300)

##### PDF
[https://arxiv.org/pdf/1511.02300](https://arxiv.org/pdf/1511.02300)

