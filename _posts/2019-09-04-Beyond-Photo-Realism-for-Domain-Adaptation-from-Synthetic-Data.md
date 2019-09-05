---
layout: post
title: "Beyond Photo Realism for Domain Adaptation from Synthetic Data"
date: 2019-09-04 17:38:05
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Kristofer Schlachter, Connor DeFanti, Sebastian Herscher, Ken Perlin, Jonathan Tompson
mathjax: true
---

* content
{:toc}

##### Abstract
As synthetic imagery is used more frequently in training deep models, it is important to understand how different synthesis techniques impact the performance of such models. In this work, we perform a thorough evaluation of the effectiveness of several different synthesis techniques and their impact on the complexity of classifier domain adaptation to the "real" underlying data distribution that they seek to replicate. In addition, we propose a novel learned synthesis technique to better train classifier models than state-of-the-art offline graphical methods, while using significantly less computational resources. We accomplish this by learning a generative model to perform shading of synthetic geometry conditioned on a "g-buffer" representation of the scene to render, as well as a low sample Monte Carlo rendered image. The major contributions are (i) a dataset that allows comparison of real and synthetic versions of the same scene, (ii) an augmented data representation that boosts the stability of learning and improves the datasets accuracy, (iii) three different partially differentiable rendering techniques where lighting, denoising and shading are learned, and (iv) we improve a state of the art generative adversarial network (GAN) approach by using an ensemble of trained models to generate datasets that approach the performance of training on real data and surpass the performance of the full global illumination rendering.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01960](http://arxiv.org/abs/1909.01960)

##### PDF
[http://arxiv.org/pdf/1909.01960](http://arxiv.org/pdf/1909.01960)

