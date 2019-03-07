---
layout: post
title: "Quantifying error contributions of computational steps, algorithms and hyperparameter choices in image classification pipelines"
date: 2019-02-25 19:16:58
categories: arXiv_CV
tags: arXiv_CV GAN Image_Classification Optimization Classification
author: Aritra Chowdhury, Malik Magdin-Ismail, Bulent Yener
mathjax: true
---

* content
{:toc}

##### Abstract
Data science relies on pipelines that are organized in the form of interdependent computational steps. Each step consists of various candidate algorithms that maybe used for performing a particular function. Each algorithm consists of several hyperparameters. Algorithms and hyperparameters must be optimized as a whole to produce the best performance. Typical machine learning pipelines typically consist of complex algorithms in each of the steps. Not only is the selection process combinatorial, but it is also important to interpret and understand the pipelines. We propose a method to quantify the importance of different layers in the pipeline, by computing an error contribution relative to an agnostic choice of algorithms in that layer. We demonstrate our methodology on image classification pipelines. The agnostic methodology quantifies the error contributions from the computational steps, algorithms and hyperparameters in the image classification pipeline. We show that algorithm selection and hyper-parameter optimization methods can be used to quantify the error contribution and that random search is able to quantify the contribution more accurately than Bayesian optimization. This methodology can be used by domain experts to understand machine learning and data analysis pipelines in terms of their individual components, which can help in prioritizing different components of the pipeline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02521](http://arxiv.org/abs/1903.02521)

##### PDF
[http://arxiv.org/pdf/1903.02521](http://arxiv.org/pdf/1903.02521)

