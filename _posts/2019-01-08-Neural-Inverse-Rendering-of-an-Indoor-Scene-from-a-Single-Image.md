---
layout: post
title: "Neural Inverse Rendering of an Indoor Scene from a Single Image"
date: 2019-01-08 17:12:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Face
author: Soumyadip Sengupta, Jinwei Gu, Kihwan Kim, Guilin Liu, David W. Jacobs, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Inverse rendering aims to estimate physical scene attributes (e.g., reflectance, geometry, and lighting) from image(s). As a long-standing, highly ill-posed problem, inverse rendering has been studied primarily for single 3D objects or with methods that solve for only one of the scene attributes. To our knowledge, we are the first to propose a holistic approach for inverse rendering of an indoor scene from a single image with CNNs, which jointly estimates reflectance (albedo and gloss), surface normals and illumination. To address the lack of labeled real-world images, we create a large-scale synthetic dataset, named SUNCG-PBR, with physically-based rendering, which is a significant improvement over prior datasets. For fine-tuning on real images, we perform self-supervised learning using the reconstruction loss, which re-synthesizes the input images from the estimated components. To enable self-supervised learning on real data, our key contribution is the Residual Appearance Renderer (RAR), which can be trained to synthesize complex appearance effects (e.g., inter-reflection, cast shadows, near-field illumination, and realistic shading), which would be neglected otherwise. Experimental results show that our approach outperforms state-of-the-art methods, especially on real images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02453](http://arxiv.org/abs/1901.02453)

##### PDF
[http://arxiv.org/pdf/1901.02453](http://arxiv.org/pdf/1901.02453)

