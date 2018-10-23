---
layout: post
title: "Unsupervised Learning of Shape and Pose with Differentiable Point Clouds"
date: 2018-10-22 16:01:20
categories: arXiv_CV
tags: arXiv_CV CNN
author: Eldar Insafutdinov, Alexey Dosovitskiy
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of learning accurate 3D shape and camera pose from a collection of unlabeled category-specific images. We train a convolutional network to predict both the shape and the pose from a single image by minimizing the reprojection error: given several views of an object, the projections of the predicted shapes to the predicted camera poses should match the provided views. To deal with pose ambiguity, we introduce an ensemble of pose predictors which we then distill to a single "student" model. To allow for efficient learning of high-fidelity shapes, we represent the shapes by point clouds and devise a formulation allowing for differentiable projection of these. Our experiments show that the distilled ensemble of pose predictors learns to estimate the pose accurately, while the point cloud representation allows to predict detailed shape models. The supplementary video can be found at https://www.youtube.com/watch?v=LuIGovKeo60

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09381](http://arxiv.org/abs/1810.09381)

##### PDF
[http://arxiv.org/pdf/1810.09381](http://arxiv.org/pdf/1810.09381)

