---
layout: post
title: "Automatic Co-Registration of Aerial Imagery and Untextured Model Data Utilizing Average Shading Gradients"
date: 2019-06-26 07:29:36
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Sylvia Schmitz, Martin Weinmann, Boitumelo Ruf
mathjax: true
---

* content
{:toc}

##### Abstract
The comparison of current image data with existing 3D model data of a scene provides an efficient method to keep models up to date. In order to transfer information between 2D and 3D data, a preliminary co-registration is necessary. In this paper, we present a concept to automatically co-register aerial imagery and untextured 3D model data. To refine a given initial camera pose, our algorithm computes dense correspondence fields using SIFT flow between gradient representations of the model and camera image, from which 2D-3D correspondences are obtained. These correspondences are then used in an iterative optimization scheme to refine the initial camera pose by minimizing the reprojection error. Since it is assumed that the model does not contain texture information, our algorithm is built up on an existing method based on Average Shading Gradients (ASG) to generate gradient images based on raw geometry information only. We apply our algorithm for the co-registering of aerial photographs to an untextured, noisy mesh model. We have investigated different magnitudes of input error and show that the proposed approach can reduce the final reprojection error to a minimum of 1.27 plus-minus 0.54 pixels, which is less than 10 % of its initial value. Furthermore, our evaluation shows that our approach outperforms the accuracy of a standard Iterative Closest Point (ICP) implementation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10882](http://arxiv.org/abs/1906.10882)

##### PDF
[http://arxiv.org/pdf/1906.10882](http://arxiv.org/pdf/1906.10882)

