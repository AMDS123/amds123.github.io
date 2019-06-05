---
layout: post
title: "Photo-Geometric Autoencoding to Learn 3D Objects from Unlabelled Images"
date: 2019-06-04 16:36:07
categories: arXiv_CV
tags: arXiv_CV Face
author: Shangzhe Wu, Christian Rupprecht, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
We show that generative models can be used to capture visual geometry constraints statistically. We use this fact to infer the 3D shape of object categories from raw single-view images. Differently from prior work, we use no external supervision, nor do we use multiple views or videos of the objects. We achieve this by a simple reconstruction task, exploiting the symmetry of the objects' shape and albedo. Specifically, given a single image of the object seen from an arbitrary viewpoint, our model predicts a symmetric canonical view, the corresponding 3D shape and a viewpoint transformation, and trains with the goal of reconstructing the input view, resembling an auto-encoder. Our experiments show that this method can recover the 3D shape of human faces, cat faces, and cars from single view images, without supervision. On benchmarks, we demonstrate superior accuracy compared to other methods that use supervision at the level of 2D image correspondences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01568](http://arxiv.org/abs/1906.01568)

##### PDF
[http://arxiv.org/pdf/1906.01568](http://arxiv.org/pdf/1906.01568)

