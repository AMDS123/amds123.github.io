---
layout: post
title: "Soft Rasterizer: A Differentiable Renderer for Image-based 3D Reasoning"
date: 2019-04-03 06:06:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Quantitative
author: Shichen Liu, Tianye Li, Weikai Chen, Hao Li
mathjax: true
---

* content
{:toc}

##### Abstract
Rendering bridges the gap between 2D vision and 3D scenes by simulating the physical process of image formation. By inverting such renderer, one can think of a learning approach to infer 3D information from 2D images. However, standard graphics renderers involve a fundamental discretization step called rasterization, which prevents the rendering process to be differentiable, hence able to be learned. Unlike the state-of-the-art differentiable renderers, which only approximate the rendering gradient in the back propagation, we propose a truly differentiable rendering framework that is able to (1) directly render colorized mesh using differentiable functions and (2) back-propagate efficient supervision signals to mesh vertices and their attributes from various forms of image representations, including silhouette, shading and color images. The key to our framework is a novel formulation that views rendering as an aggregation function that fuses the probabilistic contributions of all mesh triangles with respect to the rendered pixels. Such formulation enables our framework to flow gradients to the occluded and far-range vertices, which cannot be achieved by the previous state-of-the-arts. We show that by using the proposed renderer, one can achieve significant improvement in 3D unsupervised single-view reconstruction both qualitatively and quantitatively. Experiments also demonstrate that our approach is able to handle the challenging tasks in image-based shape fitting, which remain nontrivial to existing differentiable renderers.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01786](https://arxiv.org/abs/1904.01786)

##### PDF
[https://arxiv.org/pdf/1904.01786](https://arxiv.org/pdf/1904.01786)

