---
layout: post
title: "Deep Random Splines for Point Process Intensity Estimation of Neural Population Data"
date: 2019-06-30 00:28:06
categories: arXiv_AI
tags: arXiv_AI Inference
author: Gabriel Loaiza-Ganem, Sean M. Perkins, Karen E. Schroeder, Mark M. Churchland, John P. Cunningham
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian processes are the leading class of distributions on random functions, but they suffer from well known issues including difficulty scaling and inflexibility with respect to certain shape constraints (such as nonnegativity). Here we propose Deep Random Splines, a flexible class of random functions obtained by transforming Gaussian noise through a deep neural network whose output are the parameters of a spline. Unlike Gaussian processes, Deep Random Splines allow us to readily enforce shape constraints while inheriting the richness and tractability of deep generative models. We also present an observational model for point process data which uses Deep Random Splines to model the intensity function of each point process and apply it to neural population data to obtain a low-dimensional representation of spiking activity. Inference is performed via a variational autoencoder that uses a novel recurrent encoder architecture that can handle multiple point processes as input. We use a newly collected dataset where a primate completes a pedaling task, and observe better dimensionality reduction with our model than with competing alternatives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02610](http://arxiv.org/abs/1903.02610)

##### PDF
[http://arxiv.org/pdf/1903.02610](http://arxiv.org/pdf/1903.02610)

