---
layout: post
title: "Learning to Predict 3D Objects with an Interpolation-based Differentiable Renderer"
date: 2019-08-03 18:05:41
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction
author: Wenzheng Chen, Jun Gao, Huan Ling, Edward J. Smith, Jaakko Lehtinen, Alec Jacobson, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine learning models operate on images, but ignore the fact that images are 2D projections formed by 3D geometry interacting with light, in a process called rendering. Enabling ML models to understand image formation might be key for generalization. However, due to an essential rasterization step involving discrete assignment operations, rendering pipelines are non-differentiable and thus largely inaccessible to gradient-based ML techniques. In this paper, we present DIB-R, a differentiable rendering framework which allows gradients to be analytically computed for all pixels in an image. Key to our approach is to view foreground rasterization as a weighted interpolation of local properties and background rasterization as an distance-based aggregation of global geometry. Our approach allows for accurate optimization over vertex positions, colors, normals, light directions and texture coordinates through a variety of lighting models. We showcase our approach in two ML applications: single-image 3D object prediction, and 3D textured object generation, both trained using exclusively using 2D supervision. Our project website is: https://nv-tlabs.github.io/DIB-R/

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01210](http://arxiv.org/abs/1908.01210)

##### PDF
[http://arxiv.org/pdf/1908.01210](http://arxiv.org/pdf/1908.01210)

