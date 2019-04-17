---
layout: post
title: "Fast Inference in Capsule Networks Using Accumulated Routing Coefficients"
date: 2019-04-15 19:44:52
categories: arXiv_CV
tags: arXiv_CV Inference
author: Zhen Zhao, Ashley Kleinhans, Gursharan Sandhu, Ishan Patel, K. P. Unnikrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for fast inference in Capsule Networks (CapsNets) by taking advantage of a key insight regarding the routing coefficients that link capsules between adjacent network layers. Since the routing coefficients are responsible for assigning object parts to wholes, and an object whole generally contains similar intra-class and dissimilar inter-class parts, the routing coefficients tend to form a unique signature for each object class. For fast inference, a network is first trained in the usual manner using examples from the training dataset. Afterward, the routing coefficients associated with the training examples are accumulated offline and used to create a set of "master" routing coefficients. During inference, these master routing coefficients are used in place of the dynamically calculated routing coefficients. Our method effectively replaces the for-loop iterations in the dynamic routing procedure with a single matrix multiply operation, providing a significant boost in inference speed. Compared with the dynamic routing procedure, fast inference decreases the test accuracy for the MNIST, Background MNIST, Fashion MNIST, and Rotated MNIST datasets by less than 0.5% and by approximately 5% for CIFAR10.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07304](http://arxiv.org/abs/1904.07304)

##### PDF
[http://arxiv.org/pdf/1904.07304](http://arxiv.org/pdf/1904.07304)

