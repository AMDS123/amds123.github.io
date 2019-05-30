---
layout: post
title: "Unified Probabilistic Deep Continual Learning through Generative Replay and Open Set Recognition"
date: 2019-05-28 18:26:04
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Inference Classification Recognition
author: Martin Mundt, Sagnik Majumder, Iuliia Pliushch, Visvanathan Ramesh
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a unified probabilistic approach for deep continual learning based on variational Bayesian inference with open set recognition. Our model combines a probabilistic encoder with a generative model and a generative linear classifier that get shared across tasks. The open set recognition bounds the approximate posterior by fitting regions of high density on the basis of correctly classified data points and balances open-space risk with recognition errors. Catastrophic inference for both generative models is significantly alleviated through generative replay, where the open set recognition is used to sample from high density areas of the class specific posterior and reject statistical outliers. Our approach naturally allows for forward and backward transfer while maintaining past knowledge without the necessity of storing old data, regularization or inferring task labels. We demonstrate compelling results in the challenging scenario of incrementally expanding the single-head classifier for both class incremental visual and audio classification tasks, as well as incremental learning of datasets across modalities.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12019](http://arxiv.org/abs/1905.12019)

##### PDF
[http://arxiv.org/pdf/1905.12019](http://arxiv.org/pdf/1905.12019)

