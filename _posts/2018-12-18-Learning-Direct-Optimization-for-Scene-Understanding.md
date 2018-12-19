---
layout: post
title: "Learning Direct Optimization for Scene Understanding"
date: 2018-12-18 17:46:13
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction
author: Lukasz Romaszko, Christopher K.I. Williams, John Winn
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a Learning Direct Optimization method for the refinement of a latent variable model that describes input image x. Our goal is to explain a single image x with a 3D computer graphics model having scene graph latent variables z (such as object appearance, camera position). Given a current estimate of z we can render a prediction of the image g(z), which can be compared to the image x. The standard way to proceed is then to measure the error E(x, g(z)) between the two, and use an optimizer to minimize the error. Our novel Learning Direct Optimization (LiDO) approach trains a Prediction Network to predict an update directly to correct z, rather than minimizing the error with respect to z. Experiments show that our LiDO method converges rapidly as it does not need to perform a search on the error landscape, produces better solutions, and is able to handle the mismatch between the data and the fitted scene model. We apply the LiDO to a realistic synthetic dataset, and show that the method transfers to work well with real images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07524](http://arxiv.org/abs/1812.07524)

##### PDF
[http://arxiv.org/pdf/1812.07524](http://arxiv.org/pdf/1812.07524)

