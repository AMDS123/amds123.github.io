---
layout: post
title: "3DCarRecog: Car Recognition Using 3D Bounding Box"
date: 2019-03-19 10:17:47
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Quantitative Detection Recognition
author: Rui Zeng, Zongyuan Ge, Simon Denman, Sridha Sridharan, Clinton Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel learning framework for vehicle recognition from a single RGB image. Unlike existing methods which only use attention mechanisms to locate 2D discriminative information, our unified framework learns a 2D global texture and a 3D-bounding-box based feature representation in a mutually correlated and reinforced way. These two kinds of feature representation are combined by a novel fusion network, which predicts the vehicle's category. The 2D global feature is extracted using an off-the-shelf detection network, where the estimated 2D bounding box assists in finding the region of interest (RoI). With the assistance of the RoI, the 3D bounding box and its corresponding features are generated in a geometrically correct way using a novel 3D perspective Network (3DPN). The 3DPN consists of a convolutional neural network (CNN), a vanishing point loss, and RoI perspective layers. The CNN regresses the 3D bounding box under the guidance of the proposed vanishing point loss, which provides a perspective geometry constraint. Thanks to the proposed RoI perspective layer, the variation caused by viewpoint changes is corrected via the estimated geometry, enhancing feature representation. We present qualitative and quantitative results for our approach on the vehicle classification and verification tasks in the BoxCars dataset. The results demonstrate that, by learning how to extract features from the 3D bounding box, we can achieve comparable or superior performance to methods that only use 2D information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07916](http://arxiv.org/abs/1903.07916)

##### PDF
[http://arxiv.org/pdf/1903.07916](http://arxiv.org/pdf/1903.07916)

