---
layout: post
title: "Complete 3D Scene Parsing from an RGBD Image"
date: 2018-11-13 18:05:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Inference
author: Chuhang Zou, Ruiqi Guo, Zhizhong Li, Derek Hoiem
mathjax: true
---

* content
{:toc}

##### Abstract
One major goal of vision is to infer physical models of objects, surfaces, and their layout from sensors. In this paper, we aim to interpret indoor scenes from one RGBD image. Our representation encodes the layout of orthogonal walls and the extent of objects, modeled with CAD-like 3D shapes. We parse both the visible and occluded portions of the scene and all observable objects, producing a complete 3D parse. Such a scene interpretation is useful for robotics and visual reasoning, but difficult to produce due to the well-known challenge of segmentation, the high degree of occlusion, and the diversity of objects in indoor scenes. We take a data-driven approach, generating sets of potential object regions, matching to regions in training images, and transferring and aligning associated 3D models while encouraging fit to observations and spatial consistency. We use support inference to aid interpretation and propose a retrieval scheme that uses convolutional neural networks (CNNs) to classify regions and retrieve objects with similar shapes. We demonstrate the performance of our method on our newly annotated NYUd v2 dataset with detailed 3D shapes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1710.09490](http://arxiv.org/abs/1710.09490)

##### PDF
[http://arxiv.org/pdf/1710.09490](http://arxiv.org/pdf/1710.09490)

