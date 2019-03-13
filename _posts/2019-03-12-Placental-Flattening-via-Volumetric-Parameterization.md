---
layout: post
title: "Placental Flattening via Volumetric Parameterization"
date: 2019-03-12 16:48:23
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: S. Mazdak Abulnaga, Esra Abaci Turk, Mikhail Bessmeltsev, P. Ellen Grant, Justin Solomon, Polina Golland
mathjax: true
---

* content
{:toc}

##### Abstract
We present a volumetric mesh-based algorithm for flattening the placenta to a canonical template to enable effective visualization of local anatomy and function. Monitoring placental function in vivo promises to support pregnancy assessment and to improve care outcomes. We aim to alleviate visualization and interpretation challenges presented by the shape of the placenta when it is attached to the curved uterine wall. We flatten the volumetric mesh that captures placental shape to resemble the well-studied ex vivo shape. We formulate our method as a map from the in vivo shape to a flattened template that minimizes the symmetric Dirichlet energy density to control distortion throughout the volume. Local injectivity is enforced via constrained line search during gradient descent. We evaluate the proposed method on 28 placenta shapes extracted from MRI images in a study of placental function. We achieve sub-voxel accuracy in mapping the boundary of the placenta to the template while successfully controlling distortion throughout the volume. We illustrate how the resulting mapping of the placenta enhances visualization of the placental anatomy and function. Our code is freely available at https://github.com/mabulnaga/placenta-flattening .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05044](http://arxiv.org/abs/1903.05044)

##### PDF
[http://arxiv.org/pdf/1903.05044](http://arxiv.org/pdf/1903.05044)

