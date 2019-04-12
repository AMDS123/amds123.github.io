---
layout: post
title: "Mitigating Information Leakage in Image Representations: A Maximum Entropy Approach"
date: 2019-04-11 03:34:27
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Embedding Recognition
author: Proteek Chandan Roy, Vishnu Naresh Boddeti
mathjax: true
---

* content
{:toc}

##### Abstract
Image recognition systems have demonstrated tremendous progress over the past few decades thanks, in part, to our ability of learning compact and robust representations of images. As we witness the wide spread adoption of these systems, it is imperative to consider the problem of unintended leakage of information from an image representation, which might compromise the privacy of the data owner. This paper investigates the problem of learning an image representation that minimizes such leakage of user information. We formulate the problem as an adversarial non-zero sum game of finding a good embedding function with two competing goals: to retain as much task dependent discriminative image information as possible, while simultaneously minimizing the amount of information, as measured by entropy, about other sensitive attributes of the user. We analyze the stability and convergence dynamics of the proposed formulation using tools from non-linear systems theory and compare to that of the corresponding adversarial zero-sum game formulation that optimizes likelihood as a measure of information content. Numerical experiments on UCI, Extended Yale B, CIFAR-10 and CIFAR-100 datasets indicate that our proposed approach is able to learn image representations that exhibit high task performance while mitigating leakage of predefined sensitive information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05514](http://arxiv.org/abs/1904.05514)

##### PDF
[http://arxiv.org/pdf/1904.05514](http://arxiv.org/pdf/1904.05514)

