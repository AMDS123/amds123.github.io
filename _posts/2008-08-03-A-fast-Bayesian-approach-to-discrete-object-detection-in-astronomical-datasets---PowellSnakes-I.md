---
layout: post
title: "A fast Bayesian approach to discrete object detection in astronomical datasets - PowellSnakes I"
date: 2008-08-03 03:00:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Pedro Carvalho, Graca Rocha, M.P.Hobson
mathjax: true
---

* content
{:toc}

##### Abstract
A new fast Bayesian approach is introduced for the detection of discrete objects immersed in a diffuse background. This new method, called PowellSnakes, speeds up traditional Bayesian techniques by: i) replacing the standard form of the likelihood for the parameters characterizing the discrete objects by an alternative exact form that is much quicker to evaluate; ii) using a simultaneous multiple minimization code based on Powell's direction set algorithm to locate rapidly the local maxima in the posterior; and iii) deciding whether each located posterior peak corresponds to a real object by performing a Bayesian model selection using an approximate evidence value based on a local Gaussian approximation to the peak. The construction of this Gaussian approximation also provides the covariance matrix of the uncertainties in the derived parameter values for the object in question. This new approach provides a speed up in performance by a factor of `hundreds' as compared to existing Bayesian source extraction methods that use MCMC to explore the parameter space, such as that presented by Hobson & McLachlan. We illustrate the capabilities of the method by applying to some simplified toy models. Furthermore PowellSnakes has the advantage of consistently defining the threshold for acceptance/rejection based on priors which cannot be said of the frequentist methods. We present here the first implementation of this technique (Version-I). Further improvements to this implementation are currently under investigation and will be published shortly. The application of the method to realistic simulated Planck observations will be presented in a forthcoming publication.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/0802.3916](https://arxiv.org/abs/0802.3916)

##### PDF
[https://arxiv.org/pdf/0802.3916](https://arxiv.org/pdf/0802.3916)

