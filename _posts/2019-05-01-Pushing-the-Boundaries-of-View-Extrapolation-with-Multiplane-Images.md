---
layout: post
title: "Pushing the Boundaries of View Extrapolation with Multiplane Images"
date: 2019-05-01 17:57:09
categories: arXiv_CV
tags: arXiv_CV QA CNN Prediction
author: Pratul P. Srinivasan, Richard Tucker, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng, Noah Snavely
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the problem of view synthesis from a narrow baseline pair of images, and focus on generating high-quality view extrapolations with plausible disocclusions. Our method builds upon prior work in predicting a multiplane image (MPI), which represents scene content as a set of RGB$\alpha$ planes within a reference view frustum and renders novel views by projecting this content into the target viewpoints. We present a theoretical analysis showing how the range of views that can be rendered from an MPI increases linearly with the MPI disparity sampling frequency, as well as a novel MPI prediction procedure that theoretically enables view extrapolations of up to $4\times$ the lateral viewpoint movement allowed by prior work. Our method ameliorates two specific issues that limit the range of views renderable by prior methods: 1) We expand the range of novel views that can be rendered without depth discretization artifacts by using a 3D convolutional network architecture along with a randomized-resolution training procedure to allow our model to predict MPIs with increased disparity sampling frequency. 2) We reduce the repeated texture artifacts seen in disocclusions by enforcing a constraint that the appearance of hidden content at any depth must be drawn from visible content at or behind that depth. Please see our results video at: https://www.youtube.com/watch?v=aJqAaMNL2m4.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00413](http://arxiv.org/abs/1905.00413)

##### PDF
[http://arxiv.org/pdf/1905.00413](http://arxiv.org/pdf/1905.00413)

