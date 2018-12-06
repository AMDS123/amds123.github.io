---
layout: post
title: "Deep Bayesian Uncertainty Estimation for Adaptation and Self-Annotation of Food Packaging Images"
date: 2018-11-26 19:59:06
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification Deep_Learning Prediction
author: Fabio De Sousa Ribeiro, Francesco Caliva, Mark Swainson, Kjartan Gudmundsson, Georgios Leontidis, Stefanos Kollias
mathjax: true
---

* content
{:toc}

##### Abstract
Food packaging labels provide important information for public health, such as allergens and use-by dates. Off-the-shelf Optical Character Verification (OCV) systems are good solutions for automating food label quality assessments, but are known to under perform on complex data. This paper proposes a Deep Learning based system that can identify inadequate images for OCV, due to their poor label quality, by employing state-of-the-art Convolutional Neural Network (CNN) architectures, and practical Bayesian inference techniques for automatic self-annotation. We propose a practical domain adaptation procedure based on k-means clustering of CNN latent variables, followed by a k-Nearest Neighbour classification for handling high label variability between different dataset distributions. Moreover, Supervised Learning has proven useful in such systems but manual annotation of large amounts of data is usually required. This is practically intractable in most real world problems due to time/labour constraints. In an attempt to address this issue, we introduce a self-annotating prediction model based on Self-Training of a Bayesian CNN, that leverages modern variational inference methods of deep models. In this context, we propose a new inverse uncertainty weighting technique that encourages the Self-Training model to learn from more informative data over time, potentially preventing it from becoming lazy by only selecting easy examples to learn from. An experimental study is presented illustrating the superior performance of the proposed approach over standard Self-Training, and highlighting the importance of predictive uncertainty estimates in safety-critical domains.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01681](http://arxiv.org/abs/1812.01681)

##### PDF
[http://arxiv.org/pdf/1812.01681](http://arxiv.org/pdf/1812.01681)

