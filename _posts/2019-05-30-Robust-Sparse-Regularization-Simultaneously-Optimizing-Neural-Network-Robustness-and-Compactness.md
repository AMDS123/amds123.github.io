---
layout: post
title: "Robust Sparse Regularization: Simultaneously Optimizing Neural Network Robustness and Compactness"
date: 2019-05-30 14:32:21
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Sparse Gradient_Descent
author: Adnan Siraj Rakin, Zhezhi He, Li Yang, Yanzhi Wang, Liqiang Wang, Deliang Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Network (DNN) trained by the gradient descent method is known to be vulnerable to maliciously perturbed adversarial input, aka. adversarial attack. As one of the countermeasures against adversarial attack, increasing the model capacity for DNN robustness enhancement was discussed and reported as an effective approach by many recent works. In this work, we show that shrinking the model size through proper weight pruning can even be helpful to improve the DNN robustness under adversarial attack. For obtaining a simultaneously robust and compact DNN model, we propose a multi-objective training method called Robust Sparse Regularization (RSR), through the fusion of various regularization techniques, including channel-wise noise injection, lasso weight penalty, and adversarial training. We conduct extensive experiments across popular ResNet-20, ResNet-18 and VGG-16 DNN architectures to demonstrate the effectiveness of RSR against popular white-box (i.e., PGD and FGSM) and black-box attacks. Thanks to RSR, 85% weight connections of ResNet-18 can be pruned while still achieving 0.68% and 8.72% improvement in clean- and perturbed-data accuracy respectively on CIFAR-10 dataset, in comparison to its PGD adversarial training baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13074](http://arxiv.org/abs/1905.13074)

##### PDF
[http://arxiv.org/pdf/1905.13074](http://arxiv.org/pdf/1905.13074)

