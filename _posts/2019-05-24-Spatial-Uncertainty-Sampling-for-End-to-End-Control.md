---
layout: post
title: "Spatial Uncertainty Sampling for End-to-End Control"
date: 2019-05-24 01:10:40
categories: arXiv_AI
tags: arXiv_AI Inference Deep_Learning Relation
author: Alexander Amini, Ava Soleimany, Sertac Karaman, Daniela Rus
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end trained neural networks (NNs) are a compelling approach to autonomous vehicle control because of their ability to learn complex tasks without manual engineering of rule-based decisions. However, challenging road conditions, ambiguous navigation situations, and safety considerations require reliable uncertainty estimation for the eventual adoption of full-scale autonomous vehicles. Bayesian deep learning approaches provide a way to estimate uncertainty by approximating the posterior distribution of weights given a set of training data. Dropout training in deep NNs approximates Bayesian inference in a deep Gaussian process and can thus be used to estimate model uncertainty. In this paper, we propose a Bayesian NN for end-to-end control that estimates uncertainty by exploiting feature map correlation during training. This approach achieves improved model fits, as well as tighter uncertainty estimates, than traditional element-wise dropout. We evaluate our algorithms on a challenging dataset collected over many different road types, times of day, and weather conditions, and demonstrate how uncertainties can be used in conjunction with a human controller in a parallel autonomous setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.04829](http://arxiv.org/abs/1805.04829)

##### PDF
[http://arxiv.org/pdf/1805.04829](http://arxiv.org/pdf/1805.04829)

