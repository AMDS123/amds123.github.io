---
layout: post
title: "Plane-Based Optimization of Geometry and Texture for RGB-D Reconstruction of Indoor Scenes"
date: 2019-05-23 17:03:52
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Chao Wang, Xiaohu Guo
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach to reconstruct RGB-D indoor scene with plane primitives. Our approach takes as input a RGB-D sequence and a dense coarse mesh reconstructed by some 3D reconstruction method on the sequence, and generate a lightweight, low-polygonal mesh with clear face textures and sharp features without losing geometry details from the original scene. To achieve this, we firstly partition the input mesh with plane primitives, simplify it into a lightweight mesh next, then optimize plane parameters, camera poses and texture colors to maximize the photometric consistency across frames, and finally optimize mesh geometry to maximize consistency between geometry and planes. Compared to existing planar reconstruction methods which only cover large planar regions in the scene, our method builds the entire scene by adaptive planes without losing geometry details and preserves sharp features in the final mesh. We demonstrate the effectiveness of our approach by applying it onto several RGB-D scans and comparing it to other state-of-the-art reconstruction methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09829](http://arxiv.org/abs/1905.09829)

##### PDF
[http://arxiv.org/pdf/1905.09829](http://arxiv.org/pdf/1905.09829)

