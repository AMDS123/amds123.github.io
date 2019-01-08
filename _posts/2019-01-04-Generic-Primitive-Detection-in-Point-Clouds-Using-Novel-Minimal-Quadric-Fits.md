---
layout: post
title: "Generic Primitive Detection in Point Clouds Using Novel Minimal Quadric Fits"
date: 2019-01-04 12:09:50
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation GAN Face Quantitative Detection
author: Tolga Birdal, Benjamin Busam, Nassir Navab, Slobodan Ilic, Peter Sturm
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel and effective method for detecting 3D primitives in cluttered, unorganized point clouds, without axillary segmentation or type specification. We consider the quadric surfaces for encapsulating the basic building blocks of our environments - planes, spheres, ellipsoids, cones or cylinders, in a unified fashion. Moreover, quadrics allow us to model higher degree of freedom shapes, such as hyperboloids or paraboloids that could be used in non-rigid settings. 
 We begin by contributing two novel quadric fits targeting 3D point sets that are endowed with tangent space information. Based upon the idea of aligning the quadric gradients with the surface normals, our first formulation is exact and requires as low as four oriented points. The second fit approximates the first, and reduces the computational effort. We theoretically analyze these fits with rigor, and give algebraic and geometric arguments. Next, by re-parameterizing the solution, we devise a new local Hough voting scheme on the null-space coefficients that is combined with RANSAC, reducing the complexity from $O(N^4)$ to $O(N^3)$ (three points). To the best of our knowledge, this is the first method capable of performing a generic cross-type multi-object primitive detection in difficult scenes without segmentation. Our extensive qualitative and quantitative results show that our method is efficient and flexible, as well as being accurate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01255](http://arxiv.org/abs/1901.01255)

##### PDF
[http://arxiv.org/pdf/1901.01255](http://arxiv.org/pdf/1901.01255)

