---
layout: post
title: "Progressive Generative Adversarial Binary Networks for Music Generation"
date: 2019-03-12 04:16:20
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Manan Oza, Himanshu Vaghela, Kriti Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Recent improvements in generative adversarial network (GAN) training techniques prove that progressively training a GAN drastically stabilizes the training and improves the quality of outputs produced. Adding layers after the previous ones have converged has proven to help in better overall convergence and stability of the model as well as reducing the training time by a sufficient amount. Thus we use this training technique to train the model progressively in the time and pitch domain i.e. starting from a very small time value and pitch range we gradually expand the matrix sizes until the end result is a completely trained model giving outputs having tensor sizes [4 (bar) x 96 (time steps) x 84 (pitch values) x 8 (tracks)]. As proven in previously proposed models deterministic binary neurons also help in improving the results. Thus we make use of a layer of deterministic binary neurons at the end of the generator to get binary valued outputs instead of fractional values existing between 0 and 1.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04722](http://arxiv.org/abs/1903.04722)

##### PDF
[http://arxiv.org/pdf/1903.04722](http://arxiv.org/pdf/1903.04722)

