---
layout: post
title: "One pixel attack for fooling deep neural networks"
date: 2019-01-28 04:39:30
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Jiawei Su, Danilo Vasconcellos Vargas, Sakurai Kouichi
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research has revealed that the output of Deep Neural Networks (DNN) can be easily altered by adding relatively small perturbations to the input vector. In this paper, we analyze an attack in an extremely limited scenario where only one pixel can be modified. For that we propose a novel method for generating one-pixel adversarial perturbations based on differential evolution(DE). It requires less adversarial information(a black-box attack) and can fool more types of networks due to the inherent features of DE. The results show that 68.36% of the natural images in CIFAR-10 test dataset and 41.22% of the ImageNet (ILSVRC 2012) validation images can be perturbed to at least one target class by modifying just one pixel with 73.22% and 5.52% confidence on average. Thus, the proposed attack explores a different take on adversarial machine learning in an extreme limited scenario, showing that current DNNs are also vulnerable to such low dimension attacks. Besides, we also illustrate an important application of DE (or broadly speaking, evolutionary computation) in the domain of adversarial machine learning: creating tools that can effectively generate low-cost adversarial attacks against neural networks for evaluating robustness. The code is available on: https://github.com/Carina02/One-Pixel-Attack

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1710.08864](http://arxiv.org/abs/1710.08864)

##### PDF
[http://arxiv.org/pdf/1710.08864](http://arxiv.org/pdf/1710.08864)

