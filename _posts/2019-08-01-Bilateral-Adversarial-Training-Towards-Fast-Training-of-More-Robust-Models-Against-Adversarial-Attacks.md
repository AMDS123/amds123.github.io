---
layout: post
title: "Bilateral Adversarial Training: Towards Fast Training of More Robust Models Against Adversarial Attacks"
date: 2019-08-01 03:13:41
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Jianyu Wang, Haichao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study fast training of adversarially robust models. From the analyses of the state-of-the-art defense method, i.e., the multi-step adversarial training, we hypothesize that the gradient magnitude links to the model robustness. Motivated by this, we propose to perturb both the image and the label during training, which we call Bilateral Adversarial Training (BAT). To generate the adversarial label, we derive an closed-form heuristic solution. To generate the adversarial image, we use one-step targeted attack with the target label being the most confusing class. In the experiment, we first show that random start and the most confusing target attack effectively prevent the label leaking and gradient masking problem. Then coupled with the adversarial label part, our model significantly improves the state-of-the-art results. For example, against PGD100 white-box attack with cross-entropy loss, on CIFAR10, we achieve 63.7\% versus 47.2\%; on SVHN, we achieve 59.1\% versus 42.1\%. At last, the experiment on the very (computationally) challenging ImageNet dataset further demonstrates the effectiveness of our fast method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10716](http://arxiv.org/abs/1811.10716)

##### PDF
[http://arxiv.org/pdf/1811.10716](http://arxiv.org/pdf/1811.10716)

