---
layout: post
title: "Visual Deprojection: Probabilistic Recovery of Collapsed Dimensions"
date: 2019-09-01 21:34:28
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference
author: Guha Balakrishnan, Adrian V. Dalca, Amy Zhao, John V. Guttag, Fredo Durand, William T. Freeman
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce visual deprojection: the task of recovering an image or video that has been collapsed along a dimension. Projections arise in various contexts, such as long-exposure photography, where a dynamic scene is collapsed in time to produce a motion-blurred image, and corner cameras, where reflected light from a scene is collapsed along a spatial dimension because of an edge occluder to yield a 1D video. Deprojection is ill-posed-- often there are many plausible solutions for a given input. We first propose a probabilistic model capturing the ambiguity of the task. We then present a variational inference strategy using convolutional neural networks as functional approximators. Sampling from the inference network at test time yields plausible candidates from the distribution of original signals that are consistent with a given input projection. We evaluate the method on several datasets for both spatial and temporal deprojection tasks. We first demonstrate the method can recover human gait videos and face images from spatial projections, and then show that it can recover videos of moving digits from dramatically motion-blurred images obtained via temporal projection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00475](http://arxiv.org/abs/1909.00475)

##### PDF
[http://arxiv.org/pdf/1909.00475](http://arxiv.org/pdf/1909.00475)

