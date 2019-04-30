---
layout: post
title: "Adversarial Training for Free!"
date: 2019-04-29 17:50:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Ali Shafahi, Mahyar Najibi, Amin Ghiasi, Zheng Xu, John Dickerson, Christoph Studer, Larry S. Davis, Gavin Taylor, Tom Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial training, in which a network is trained on adversarial examples, is one of the few defenses against adversarial attacks that withstands strong attacks. Unfortunately, the high cost of generating strong adversarial examples makes standard adversarial training impractical on large-scale problems like ImageNet. We present an algorithm that eliminates the overhead cost of generating adversarial examples by recycling the gradient information computed when updating model parameters. Our "free" adversarial training algorithm achieves state-of-the-art robustness on CIFAR-10 and CIFAR-100 datasets at negligible additional cost compared to natural training, and can be 7 to 30 times faster than other strong adversarial training methods. Using a single workstation with 4 P100 GPUs and 2 days of runtime, we can train a robust model for the large-scale ImageNet classification task that maintains 40% accuracy against PGD attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12843](http://arxiv.org/abs/1904.12843)

##### PDF
[http://arxiv.org/pdf/1904.12843](http://arxiv.org/pdf/1904.12843)

