---
layout: post
title: "Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks"
date: 2018-11-10 15:37:17
categories: arXiv_CV
tags: arXiv_CV Face Transfer_Learning Optimization Recognition Face_Recognition
author: Ali Shafahi, W. Ronny Huang, Mahyar Najibi, Octavian Suciu, Christoph Studer, Tudor Dumitras, Tom Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Data poisoning is an attack on machine learning models wherein the attacker adds examples to the training set to manipulate the behavior of the model at test time. This paper explores poisoning attacks on neural nets. The proposed attacks use "clean-labels"; they don't require the attacker to have any control over the labeling of training data. They are also targeted; they control the behavior of the classifier on a $\textit{specific}$ test instance without degrading overall classifier performance. For example, an attacker could add a seemingly innocuous image (that is properly labeled) to a training set for a face recognition engine, and control the identity of a chosen person at test time. Because the attacker does not need to control the labeling function, poisons could be entered into the training set simply by leaving them on the web and waiting for them to be scraped by a data collection bot. 
 We present an optimization-based method for crafting poisons, and show that just one single poison image can control classifier behavior when transfer learning is used. For full end-to-end training, we present a "watermarking" strategy that makes poisoning reliable using multiple ($\approx$50) poisoned training instances. We demonstrate our method by generating poisoned frog images from the CIFAR dataset and using them to manipulate image classifiers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.00792](http://arxiv.org/abs/1804.00792)

##### PDF
[http://arxiv.org/pdf/1804.00792](http://arxiv.org/pdf/1804.00792)

