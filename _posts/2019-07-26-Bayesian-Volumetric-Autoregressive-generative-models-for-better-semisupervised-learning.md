---
layout: post
title: "Bayesian Volumetric Autoregressive generative models for better semisupervised learning"
date: 2019-07-26 13:08:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Guilherme Pombo, Robert Gray, Tom Varsavsky, John Ashburner, Parashkev Nachev
mathjax: true
---

* content
{:toc}

##### Abstract
Deep generative models are rapidly gaining traction in medical imaging. Nonetheless, most generative architectures struggle to capture the underlying probability distributions of volumetric data, exhibit convergence problems, and offer no robust indices of model uncertainty. By comparison, the autoregressive generative model PixelCNN can be extended to volumetric data with relative ease, it readily attempts to learn the true underlying probability distribution and it still admits a Bayesian reformulation that provides a principled framework for reasoning about model uncertainty. Our contributions in this paper are two fold: first, we extend PixelCNN to work with volumetric brain magnetic resonance imaging data. Second, we show that reformulating this model to approximate a deep Gaussian process yields a measure of uncertainty that improves the performance of semi-supervised learning, in particular classification performance in settings where the proportion of labelled data is low. We quantify this improvement across classification, regression, and semantic segmentation tasks, training and testing on clinical magnetic resonance brain imaging data comprising T1-weighted and diffusion-weighted sequences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11559](http://arxiv.org/abs/1907.11559)

##### PDF
[http://arxiv.org/pdf/1907.11559](http://arxiv.org/pdf/1907.11559)

