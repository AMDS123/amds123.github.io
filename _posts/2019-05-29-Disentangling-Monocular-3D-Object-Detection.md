---
layout: post
title: "Disentangling Monocular 3D Object Detection"
date: 2019-05-29 12:13:53
categories: arXiv_CV
tags: arXiv_CV Review Object_Detection Detection
author: Andrea Simonelli, Samuel Rota Rota Bul&#xf2;, Lorenzo Porzi, Manuel L&#xf3;pez-Antequera, Peter Kontschieder
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an approach for monocular 3D object detection from a single RGB image, which leverages a novel disentangling transformation for 2D and 3D detection losses and a novel, self-supervised confidence score for 3D bounding boxes. Our proposed loss disentanglement has the twofold advantage of simplifying the training dynamics in the presence of losses with complex interactions of parameters, and sidestepping the issue of balancing independent regression terms. Our solution overcomes these issues by isolating the contribution made by groups of parameters to a given loss, without changing its nature. We further apply loss disentanglement to another novel, signed Intersection-over-Union criterion-driven loss for improving 2D detection results. Besides our methodological innovations, we critically review the AP metric used in KITTI3D, which emerged as the most important dataset for comparing 3D detection results. We identify and resolve a flaw in the 11-point interpolated AP metric, affecting all previously published detection results and particularly biases the results of monocular 3D detection. We provide extensive experimental evaluations and ablation studies on the KITTI3D and nuScenes datasets, setting new state-of-the-art results on object category car by large margins.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12365](http://arxiv.org/abs/1905.12365)

##### PDF
[http://arxiv.org/pdf/1905.12365](http://arxiv.org/pdf/1905.12365)

