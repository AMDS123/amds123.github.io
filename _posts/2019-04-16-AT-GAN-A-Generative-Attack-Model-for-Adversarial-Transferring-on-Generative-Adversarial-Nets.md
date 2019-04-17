---
layout: post
title: "AT-GAN: A Generative Attack Model for Adversarial Transferring on Generative Adversarial Nets"
date: 2019-04-16 16:26:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Xiaosen Wang, Kun He, Chuan Guo, Kilian Q. Weinberger, John E. Hopcroft
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies have discovered the vulnerability of Deep Neural Networks (DNNs) to adversarial examples, which are imperceptible to humans but can easily fool DNNs. Existing methods for crafting adversarial examples are mainly based on adding small-magnitude perturbations to the original images so that the generated adversarial examples are constrained by the benign examples within a small matrix norm. In this work, we propose a new attack method called AT-GAN that directly generates the adversarial examples from random noise using generative adversarial nets (GANs). The key idea is to transfer a pre-trained GAN to generate adversarial examples for the target classifier to be attacked. Once the model is transferred for attack, AT-GAN can generate diverse adversarial examples efficiently, making it helpful to potentially accelerate the adversarial training on defenses. We evaluate AT-GAN in both semi-whitebox and black-box settings under typical defense methods on the MNIST handwritten digit database. Empirical comparisons with existing attack baselines demonstrate that AT-GAN can achieve a higher attack success rate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07793](http://arxiv.org/abs/1904.07793)

##### PDF
[http://arxiv.org/pdf/1904.07793](http://arxiv.org/pdf/1904.07793)

