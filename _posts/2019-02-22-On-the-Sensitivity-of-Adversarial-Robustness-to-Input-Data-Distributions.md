---
layout: post
title: "On the Sensitivity of Adversarial Robustness to Input Data Distributions"
date: 2019-02-22 02:03:17
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Gavin Weiguang Ding, Kry Yik Chau Lui, Xiaomeng Jin, Luyu Wang, Ruitong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are vulnerable to small adversarial perturbations. Existing literature largely focused on understanding and mitigating the vulnerability of learned models. In this paper, we demonstrate an intriguing phenomenon about the most popular robust training method in the literature, adversarial training: Adversarial robustness, unlike clean accuracy, is sensitive to the input data distribution. Even a semantics-preserving transformations on the input data distribution can cause a significantly different robustness for the adversarial trained model that is both trained and evaluated on the new distribution. Our discovery of such sensitivity on data distribution is based on a study which disentangles the behaviors of clean accuracy and robust accuracy of the Bayes classifier. Empirical investigations further confirm our finding. We construct semantically-identical variants for MNIST and CIFAR10 respectively, and show that standardly trained models achieve comparable clean accuracies on them, but adversarially trained models achieve significantly different robustness accuracies. This counter-intuitive phenomenon indicates that input data distribution alone can affect the adversarial robustness of trained neural networks, not necessarily the tasks themselves. Lastly, we discuss the practical implications on evaluating adversarial robustness, and make initial attempts to understand this complex phenomenon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08336](http://arxiv.org/abs/1902.08336)

##### PDF
[http://arxiv.org/pdf/1902.08336](http://arxiv.org/pdf/1902.08336)

