---
layout: post
title: "Star-convex Polyhedra for 3D Object Detection and Segmentation in Microscopy"
date: 2019-08-09 21:22:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Martin Weigert, Uwe Schmidt, Robert Haase, Ko Sugawara, Gene Myers
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate detection and segmentation of cell nuclei in volumetric (3D) fluorescence microscopy datasets is an important step in many biomedical research projects. Although many automated methods for these tasks exist, they often struggle for images with low signal-to-noise ratios and/or dense packing of nuclei. It was recently shown for 2D microscopy images that these issues can be alleviated by training a neural network to directly predict a suitable shape representation (star-convex polygon) for cell nuclei. In this paper, we adopt and extend this approach to 3D volumes by using star-convex polyhedra to represent cell nuclei and similar shapes. To that end, we overcome the challenges of 1) finding parameter-efficient star-convex polyhedra representations that can faithfully describe cell nuclei shapes, 2) adapting to anisotropic voxel sizes often found in fluorescence microscopy datasets, and 3) efficiently computing intersections between pairs of star-convex polyhedra (required for non-maximum suppression). Although our approach is quite general, since star-convex polyhedra subsume common shapes like bounding boxes and spheres as special cases, our focus is on accurate detection and segmentation of cell nuclei. That that end, we demonstrate on two challenging datasets that our approach (StarDist-3D) leads to superior results when compared to classical and deep-learning based methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03636](https://arxiv.org/abs/1908.03636)

##### PDF
[https://arxiv.org/pdf/1908.03636](https://arxiv.org/pdf/1908.03636)

