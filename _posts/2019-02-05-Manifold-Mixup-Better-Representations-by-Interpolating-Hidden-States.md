---
layout: post
title: "Manifold Mixup: Better Representations by Interpolating Hidden States"
date: 2019-02-05 18:18:18
categories: arXiv_AI
tags: arXiv_AI Adversarial Prediction
author: Vikas Verma, Alex Lamb, Christopher Beckham, Amir Najafi, Ioannis Mitliagkas, Aaron Courville, David Lopez-Paz, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks excel at learning the training data, but often provide incorrect and confident predictions when evaluated on slightly different test examples. This includes distribution shifts, outliers, and adversarial examples. To address these issues, we propose \manifoldmixup{}, a simple regularizer that encourages neural networks to predict less confidently on interpolations of hidden representations. \manifoldmixup{} leverages semantic interpolations as additional training signal, obtaining neural networks with smoother decision boundaries at multiple levels of representation. As a result, neural networks trained with \manifoldmixup{} learn class-representations with fewer directions of variance. We prove theory on why this flattening happens under ideal conditions, validate it on practical situations, and connect it to previous works on information theory and generalization. In spite of incurring no significant computation and being implemented in a few lines of code, \manifoldmixup{} improves strong baselines in supervised learning, robustness to single-step adversarial attacks, and test log-likelihood.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.05236](http://arxiv.org/abs/1806.05236)

##### PDF
[http://arxiv.org/pdf/1806.05236](http://arxiv.org/pdf/1806.05236)

