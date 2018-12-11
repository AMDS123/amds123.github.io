---
layout: post
title: "Feature Denoising for Improving Adversarial Robustness"
date: 2018-12-09 01:55:31
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Image_Classification Classification
author: Cihang Xie, Yuxin Wu, Laurens van der Maaten, Alan Yuille, Kaiming He
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial attacks to image classification systems present challenges to convolutional networks and opportunities for understanding them. This study suggests that adversarial perturbations on images lead to noise in the features constructed by these networks. Motivated by this observation, we develop new network architectures that increase adversarial robustness by performing feature denoising. Specifically, our networks contain blocks that denoise the features using non-local means or other filters; the entire networks are trained end-to-end. When combined with adversarial training, our feature denoising networks substantially improve the state-of-the-art in adversarial robustness in both white-box and black-box attack settings. On ImageNet, under 10-iteration PGD white-box attacks where prior art has 27.9% accuracy, our method achieves 55.7%; even under extreme 2000-iteration PGD white-box attacks, our method secures 42.6% accuracy. A network based on our method was ranked first in Competition on Adversarial Attacks and Defenses (CAAD) 2018 --- it achieved 50.6% classification accuracy on a secret, ImageNet-like test dataset against 48 unknown attackers, surpassing the runner-up approach by ~10%. Code and models will be made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03411](http://arxiv.org/abs/1812.03411)

##### PDF
[http://arxiv.org/pdf/1812.03411](http://arxiv.org/pdf/1812.03411)

