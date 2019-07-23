---
layout: post
title: "Image-and-Spatial Transformer Networks for Structure-Guided Image Registration"
date: 2019-07-22 09:39:53
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation
author: Matthew C.H. Lee, Ozan Oktay, Andreas Schuh, Michiel Schaap, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
Image registration with deep neural networks has become an active field of research and exciting avenue for a long standing problem in medical imaging. The goal is to learn a complex function that maps the appearance of input image pairs to parameters of a spatial transformation in order to align corresponding anatomical structures. We argue and show that the current direct, non-iterative approaches are sub-optimal, in particular if we seek accurate alignment of Structures-of-Interest (SoI). Information about SoI is often available at training time, for example, in form of segmentations or landmarks. We introduce a novel, generic framework, Image-and-Spatial Transformer Networks (ISTNs), to leverage SoI information allowing us to learn new image representations that are optimised for the downstream registration task. Thanks to these representations we can employ a test-specific, iterative refinement over the transformation parameters which yields highly accurate registration even with very limited training data. Performance is demonstrated on pairwise 3D brain registration and illustrative synthetic data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09200](http://arxiv.org/abs/1907.09200)

##### PDF
[http://arxiv.org/pdf/1907.09200](http://arxiv.org/pdf/1907.09200)

