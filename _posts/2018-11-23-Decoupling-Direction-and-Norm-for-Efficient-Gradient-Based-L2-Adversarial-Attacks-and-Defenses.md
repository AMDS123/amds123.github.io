---
layout: post
title: "Decoupling Direction and Norm for Efficient Gradient-Based L2 Adversarial Attacks and Defenses"
date: 2018-11-23 18:54:47
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Classification
author: J&#xe9;r&#xf4;me Rony, Luiz G. Hafemann, Luis S. Oliveira, Ismail Ben Ayed, Robert Sabourin, Eric Granger
mathjax: true
---

* content
{:toc}

##### Abstract
Research on adversarial examples in computer vision tasks has shown that small, often imperceptible changes to an image can induce misclassification, which has security implications for a wide range of image processing systems. Considering $L_2$ norm distortions, the Carlini and Wagner attack is presently the most effective white-box attack in the literature. However, this method is slow since it performs a line-search for one of the optimization terms, and often requires thousands of iterations. In this paper, an efficient approach is proposed to generate gradient-based attacks that induce misclassifications with low $L_2$ norm, by decoupling the direction and the norm of the adversarial perturbation that is added to the image. Experiments conducted on the MNIST, CIFAR-10 and ImageNet datasets indicate that our attack achieves comparable results to the state-of-the-art (in terms of $L_2$ norm) with considerably fewer iterations (as few as 100 iterations), which opens the possibility of using these attacks for adversarial training. Models trained with our attack achieve state-of-the-art robustness against white-box gradient-based $L_2$ attacks on the MNIST and CIFAR-10 datasets, outperforming the Madry defense when the attacks are limited to a maximum norm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09600](http://arxiv.org/abs/1811.09600)

##### PDF
[http://arxiv.org/pdf/1811.09600](http://arxiv.org/pdf/1811.09600)

