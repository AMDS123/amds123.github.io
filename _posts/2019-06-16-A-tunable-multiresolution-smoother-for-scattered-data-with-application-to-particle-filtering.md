---
layout: post
title: "A tunable multiresolution smoother for scattered data with application to particle filtering"
date: 2019-06-16 16:27:52
categories: arXiv_CV
tags: arXiv_CV
author: Gregor A. Robinson, Ian G. Grooms
mathjax: true
---

* content
{:toc}

##### Abstract
A smoothing algorithm is presented that can reduce the small-scale content of data observed at scattered locations in a spatially extended domain. The smoother works by forming a Gaussian interpolant of the input data, and then convolving the interpolant with a multiresolution Gaussian approximation of the Green's function to a differential operator whose spectrum can be tuned for problem-specific considerations. This smoother is developed for its potential application to particle filtering, which often involves data scattered over a spatial domain, since preprocessing observations with a smoother reduces the ensemble size required to avoid particle filter collapse. An example on meteorological data verifies that our smoother improves the balance of particle filter weights.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06722](http://arxiv.org/abs/1906.06722)

##### PDF
[http://arxiv.org/pdf/1906.06722](http://arxiv.org/pdf/1906.06722)

