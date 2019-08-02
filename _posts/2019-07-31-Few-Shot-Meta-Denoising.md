---
layout: post
title: "Few-Shot Meta-Denoising"
date: 2019-07-31 21:40:44
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning
author: Leslie Casas, Gustavo Carneiro, Nassir Navab, Vasileios Belagiannis
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of learning-based denoising where the training set contains just a handful of clean and noisy samples. A solution to mitigate the small training set issue is to train a denoising model with pairs of clean and synthesized noisy signals, produced from empirical noise priors; and finally only fine-tune on the available small training set. While transfer learning suits well to this pipeline, it does not generalize with the limited amount of training data. In this work, we propose a new training approach, based on meta-learning, for few-shot learning-based denoising problems. Our model is meta-trained using known synthetic noise models, and then fine-tuned with the small training set, with the real noise, as a few-shot learning task. Learning from synthetic data during meta-training gives us the ability to generate an infinite number of training data. Our approach is empirically shown to produce more accurate denoising results than supervised learning and transfer learning in three denoising evaluations for images and 1-D signals. Interestingly, our study provides strong indications that meta-learning has the potential to become the main learning algorithm for the denoising.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00111](http://arxiv.org/abs/1908.00111)

##### PDF
[http://arxiv.org/pdf/1908.00111](http://arxiv.org/pdf/1908.00111)

