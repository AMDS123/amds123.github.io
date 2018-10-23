---
layout: post
title: "ReTiCaM: Real-time Human Performance Capture from Monocular Video"
date: 2018-10-22 14:29:54
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking Optimization Detection
author: Marc Habermann, Weipeng Xu, Michael Zollhoefer, Gerard Pons-Moll, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first real-time human performance capture approach that reconstructs dense, space-time coherent deforming geometry of entire humans in general everyday clothing from just a single RGB video. We propose a novel two-stage analysis-by-synthesis optimization whose formulation and implementation are designed for high performance. In the first stage, a skinned template model is jointly fitted to background subtracted input video, 2D and 3D skeleton joint positions found using a deep neural network, and a set of sparse facial landmark detections. In the second stage, dense non-rigid 3D deformations of skin and even loose apparel are captured based on a novel real-time capable algorithm for non-rigid tracking using dense photometric and silhouette constraints. Our novel energy formulation leverages automatically identified material regions on the template to model the differing non-rigid deformation behavior of skin and apparel. The two resulting non-linear optimization problems per-frame are solved with specially-tailored data-parallel Gauss-Newton solvers. In order to achieve real-time performance of over 25Hz, we design a pipelined parallel architecture using the CPU and two commodity GPUs. Our method is the first real-time monocular approach for full-body performance capture. Our method yields comparable accuracy with off-line performance capture techniques, while being orders of magnitude faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.02648](http://arxiv.org/abs/1810.02648)

##### PDF
[http://arxiv.org/pdf/1810.02648](http://arxiv.org/pdf/1810.02648)

