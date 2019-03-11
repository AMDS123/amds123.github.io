---
layout: post
title: "Stable Backward Diffusion Models that Minimise Convex Energies"
date: 2019-03-08 15:15:14
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement Gradient_Descent
author: Leif Bergerhoff, Marcelo C&#xe1;rdenas, Joachim Weickert, Martin Welk
mathjax: true
---

* content
{:toc}

##### Abstract
Backward diffusion processes appear naturally in image enhancement and deblurring applications. However, the inverse problem of backward diffusion is known to be ill-posed and straightforward numerical algorithms are unstable. So far, existing stabilisation strategies in the literature require sophisticated numerics to solve the underlying initial value problem. Therefore, it is desirable to establish a backward diffusion model which implements a smart stabilisation approach that can be used in combination with a simple numerical scheme. We derive a class of space-discrete one-dimensional backward diffusion as gradient descent of energies where we gain stability by imposing range constraints. Interestingly, these energies are even convex. Furthermore, we establish a comprehensive theory for the time-continuous evolution and we show that stability carries over to a simple explicit time discretisation of our model. Finally, we confirm the stability and usefulness of our technique in experiments in which we enhance the contrast of digital greyscale and colour images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03491](http://arxiv.org/abs/1903.03491)

##### PDF
[http://arxiv.org/pdf/1903.03491](http://arxiv.org/pdf/1903.03491)

