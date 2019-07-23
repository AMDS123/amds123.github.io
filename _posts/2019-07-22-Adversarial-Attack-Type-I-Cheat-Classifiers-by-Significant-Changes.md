---
layout: post
title: "Adversarial Attack Type I: Cheat Classifiers by Significant Changes"
date: 2019-07-22 13:00:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Face Detection
author: Sanli Tang, Xiaolin Huang, Mingjian Chen, Chengjin Sun, Jie Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the great success of deep neural networks, the adversarial attack can cheat some well-trained classifiers by small permutations. In this paper, we propose another type of adversarial attack that can cheat classifiers by significant changes. For example, we can significantly change a face but well-trained neural networks still recognize the adversarial and the original example as the same person. Statistically, the existing adversarial attack increases Type II error and the proposed one aims at Type I error, which are hence named as Type II and Type I adversarial attack, respectively. The two types of attack are equally important but are essentially different, which are intuitively explained and numerically evaluated. To implement the proposed attack, a supervised variation autoencoder is designed and then the classifier is attacked by updating the latent variables using gradient information. {Besides, with pre-trained generative models, Type I attack on latent spaces is investigated as well.} Experimental results show that our method is practical and effective to generate Type I adversarial examples on large-scale image datasets. Most of these generated examples can pass detectors designed for defending Type II attack and the strengthening strategy is only efficient with a specific type attack, both implying that the underlying reasons for Type I and Type II attack are different.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.00594](http://arxiv.org/abs/1809.00594)

##### PDF
[http://arxiv.org/pdf/1809.00594](http://arxiv.org/pdf/1809.00594)

