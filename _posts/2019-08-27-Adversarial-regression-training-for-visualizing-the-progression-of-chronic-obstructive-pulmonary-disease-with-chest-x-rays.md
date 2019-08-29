---
layout: post
title: "Adversarial regression training for visualizing the progression of chronic obstructive pulmonary disease with chest x-rays"
date: 2019-08-27 21:14:12
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Classification Deep_Learning
author: Ricardo Bigolin Lanfredi, Joyce D. Schroeder, Clement Vachet, Tolga Tasdizen
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge of what spatial elements of medical images deep learning methods use as evidence is important for model interpretability, trustiness, and validation. There is a lack of such techniques for models in regression tasks. We propose a method, called visualization for regression with a generative adversarial network (VR-GAN), for formulating adversarial training specifically for datasets containing regression target values characterizing disease severity. We use a conditional generative adversarial network where the generator attempts to learn to shift the output of a regressor through creating disease effect maps that are added to the original images. Meanwhile, the regressor is trained to predict the original regression value for the modified images. A model trained with this technique learns to provide visualization for how the image would appear at different stages of the disease. We analyze our method in a dataset of chest x-rays associated with pulmonary function tests, used for diagnosing chronic obstructive pulmonary disease (COPD). For validation, we compute the difference of two registered x-rays of the same patient at different time points and correlate it to the generated disease effect map. The proposed method outperforms a technique based on classification and provides realistic-looking images, making modifications to images following what radiologists usually observe for this disease. Implementation code is available at https://github.com/ricbl/vrgan.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10468](http://arxiv.org/abs/1908.10468)

##### PDF
[http://arxiv.org/pdf/1908.10468](http://arxiv.org/pdf/1908.10468)

