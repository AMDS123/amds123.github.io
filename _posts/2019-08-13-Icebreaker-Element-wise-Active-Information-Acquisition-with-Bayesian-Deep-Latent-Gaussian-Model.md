---
layout: post
title: "Icebreaker: Element-wise Active Information Acquisition with Bayesian Deep Latent Gaussian Model"
date: 2019-08-13 08:49:33
categories: arXiv_AI
tags: arXiv_AI Inference Prediction Recommendation
author: Wenbo Gong, Sebastian Tschiatschek, Richard Turner, Sebastian Nowozin, Jos&#xe9; Miguel Hern&#xe1;ndez-Lobato
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce the ice-start problem, i.e., the challenge of deploying machine learning models when only little or no training data is initially available, and acquiring each feature element of data is associated with costs. This setting is representative for the real-world machine learning applications. For instance, in the health-care domain, when training an AI system for predicting patient metrics from lab tests, obtaining every single measurement comes with a high cost. Active learning, where only the label is associated with a cost does not apply to such problem, because performing all possible lab tests to acquire a new training datum would be costly, as well as unnecessary due to redundancy. We propose Icebreaker, a principled framework to approach the ice-start problem. Icebreaker uses a full Bayesian Deep Latent Gaussian Model (BELGAM) with a novel inference method. Our proposed method combines recent advances in amortized inference and stochastic gradient MCMC to enable fast and accurate posterior inference. By utilizing BELGAM's ability to fully quantify model uncertainty, we also propose two information acquisition functions for imputation and active prediction problems. We demonstrate that BELGAM performs significantly better than the previous VAE (Variational autoencoder) based models, when the data set size is small, using both machine learning benchmarks and real-world recommender systems and health-care applications. Moreover, based on BELGAM, Icebreaker further improves the performance and demonstrate the ability to use minimum amount of the training data to obtain the highest test time performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04537](http://arxiv.org/abs/1908.04537)

##### PDF
[http://arxiv.org/pdf/1908.04537](http://arxiv.org/pdf/1908.04537)

