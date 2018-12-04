---
layout: post
title: "Constructing Unrestricted Adversarial Examples with Generative Models"
date: 2018-12-02 22:18:56
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Yang Song, Rui Shu, Nate Kushman, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples are typically constructed by perturbing an existing data point within a small matrix norm, and current defense methods are focused on guarding against this type of attack. In this paper, we propose unrestricted adversarial examples, a new threat model where the attackers are not restricted to small norm-bounded perturbations. Different from perturbation-based attacks, we propose to synthesize unrestricted adversarial examples entirely from scratch using conditional generative models. Specifically, we first train an Auxiliary Classifier Generative Adversarial Network (AC-GAN) to model the class-conditional distribution over data samples. Then, conditioned on a desired class, we search over the AC-GAN latent space to find images that are likely under the generative model and are misclassified by a target classifier. We demonstrate through human evaluation that unrestricted adversarial examples generated this way are legitimate and belong to the desired class. Our empirical results on the MNIST, SVHN, and CelebA datasets show that unrestricted adversarial examples can bypass strong adversarial training and certified defense methods designed for traditional adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07894](http://arxiv.org/abs/1805.07894)

##### PDF
[http://arxiv.org/pdf/1805.07894](http://arxiv.org/pdf/1805.07894)

