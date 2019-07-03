---
layout: post
title: "A Closest Point Proposal for MCMC-based Probabilistic Surface Registration"
date: 2019-07-02 14:43:22
categories: arXiv_CV
tags: arXiv_CV Face Inference
author: Dennis Madsen, Andreas Morel-Forster, Patrick Kahr, Dana Rahbani, Thomas Vetter, Marcel L&#xfc;thi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a non-rigid surface registration algorithm that estimates the correspondence uncertainty using the Markov-chain Monte Carlo (MCMC) framework. The estimated uncertainty of the inferred registration is important for many applications, such as surgical planning or missing data reconstruction. The used Metropolis-Hastings (MH) algorithm decouples the inference from modelling the posterior using a propose-and-verify scheme. The widely used random sampling strategy leads to slow convergence rates in high dimensional space. In order to overcome this limitation, we introduce an informed probabilistic proposal based on ICP that can be used within the MH algorithm. While the ICP algorithm is used in the inference algorithm, the likelihood can be chosen independently. We showcase different surface distance measures, such as the traditional Euclidean norm and the Hausdorff distance. While quantifying the uncertainty of the correspondence, we also experimentally verify that our method is more robust than the non-rigid ICP algorithm and provides more accurate surface registrations. In a reconstruction task, we show how our probabilistic framework can be used to estimate the posterior distribution of missing data without assuming a fixed point-to-point correspondence. We have made our registration framework publicly available for the community.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01414](http://arxiv.org/abs/1907.01414)

##### PDF
[http://arxiv.org/pdf/1907.01414](http://arxiv.org/pdf/1907.01414)

