---
layout: post
title: "Universal Adversarial Training"
date: 2018-11-27 23:09:27
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization
author: Ali Shafahi, Mahyar Najibi, Zheng Xu, John Dickerson, Larry S. Davis, Tom Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Standard adversarial attacks change the predicted class label of an image by adding specially tailored small perturbations to its pixels. In contrast, a universal perturbation is an update that can be added to any image in a broad class of images, while still changing the predicted class label. We study the efficient generation of universal adversarial perturbations, and also efficient methods for hardening networks to these attacks. We propose a simple optimization-based universal attack that reduces the top-1 accuracy of various network architectures on ImageNet to less than 20%, while learning the universal perturbation 13X faster than the standard method. To defend against these perturbations, we propose universal adversarial training, which models the problem of robust classifier generation as a two-player min-max game. This method is much faster and more scalable than conventional adversarial training with a strong adversary (PGD), and yet yields models that are extremely resistant to universal attacks, and comparably resistant to standard (per-instance) black box attacks. We also discover a rather fascinating side-effect of universal adversarial training: attacks built for universally robust models transfer better to other (black box) models than those built with conventional adversarial training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11304](http://arxiv.org/abs/1811.11304)

##### PDF
[http://arxiv.org/pdf/1811.11304](http://arxiv.org/pdf/1811.11304)

