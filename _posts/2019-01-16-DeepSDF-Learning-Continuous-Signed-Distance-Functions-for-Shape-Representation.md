---
layout: post
title: "DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation"
date: 2019-01-16 01:21:27
categories: arXiv_CV
tags: arXiv_CV Face Classification
author: Jeong Joon Park, Peter Florence, Julian Straub, Richard Newcombe, Steven Lovegrove
mathjax: true
---

* content
{:toc}

##### Abstract
Computer graphics, 3D computer vision and robotics communities have produced multiple approaches to representing 3D geometry for rendering and reconstruction. These provide trade-offs across fidelity, efficiency and compression capabilities. In this work, we introduce DeepSDF, a learned continuous Signed Distance Function (SDF) representation of a class of shapes that enables high quality shape representation, interpolation and completion from partial and noisy 3D input data. DeepSDF, like its classical counterpart, represents a shape's surface by a continuous volumetric field: the magnitude of a point in the field represents the distance to the surface boundary and the sign indicates whether the region is inside (-) or outside (+) of the shape, hence our representation implicitly encodes a shape's boundary as the zero-level-set of the learned function while explicitly representing the classification of space as being part of the shapes interior or not. While classical SDF's both in analytical or discretized voxel form typically represent the surface of a single shape, DeepSDF can represent an entire class of shapes. Furthermore, we show state-of-the-art performance for learned 3D shape representation and completion while reducing the model size by an order of magnitude compared with previous work.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05103](http://arxiv.org/abs/1901.05103)

##### PDF
[http://arxiv.org/pdf/1901.05103](http://arxiv.org/pdf/1901.05103)

