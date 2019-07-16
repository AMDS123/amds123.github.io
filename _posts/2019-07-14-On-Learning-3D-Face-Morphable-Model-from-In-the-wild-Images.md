---
layout: post
title: "On Learning 3D Face Morphable Model from In-the-wild Images"
date: 2019-07-14 05:01:58
categories: arXiv_CV
tags: arXiv_CV Face
author: Luan Tran, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
As a classic statistical model of 3D facial shape and albedo, 3D Morphable Model (3DMM) is widely used in facial analysis, e.g., model fitting, image synthesis. Conventional 3DMM is learned from a set of 3D face scans with associated well-controlled 2D face images, and represented by two sets of PCA basis functions. Due to the type and amount of training data, as well as, the linear bases, the representation power of 3DMM can be limited. To address these problems, this paper proposes an innovative framework to learn a nonlinear 3DMM model from a large set of in-the-wild face images, without collecting 3D face scans. Specifically, given a face image as input, a network encoder estimates the projection, lighting, shape and albedo parameters. Two decoders serve as the nonlinear 3DMM to map from the shape and albedo parameters to the 3D shape and albedo, respectively. With the projection parameter, lighting, 3D shape, and albedo, a novel analytically-differentiable rendering layer is designed to reconstruct the original input face. The entire network is end-to-end trainable with only weak supervision. We demonstrate the superior representation power of our nonlinear 3DMM over its linear counterpart, and its contribution to face alignment, 3D reconstruction, and face editing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.09560](http://arxiv.org/abs/1808.09560)

##### PDF
[http://arxiv.org/pdf/1808.09560](http://arxiv.org/pdf/1808.09560)

