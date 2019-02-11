---
layout: post
title: "Understanding the One-Pixel Attack: Propagation Maps and Locality Analysis"
date: 2019-02-08 06:06:01
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Danilo Vasconcellos Vargas, Jiawei Su
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks were shown to be vulnerable to single pixel modifications. However, the reason behind such phenomena has never been elucidated. Here, we propose Propagation Maps which show the influence of the perturbation in each layer of the network. Propagation Maps reveal that even in extremely deep networks such as Resnet, modification in one pixel easily propagates until the last layer. In fact, this initial local perturbation is also shown to spread becoming a global one and reaching absolute difference values that are close to the maximum value of the original feature maps in a given layer. Moreover, we do a locality analysis in which we demonstrate that nearby pixels of the perturbed one in the one-pixel attack tend to share the same vulnerability, revealing that the main vulnerability lies in neither neurons nor pixels but receptive fields. Hopefully, the analysis conducted in this work together with a new technique called propagation maps shall shed light into the inner workings of other adversarial samples and be the basis of new defense systems to come.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02947](http://arxiv.org/abs/1902.02947)

##### PDF
[http://arxiv.org/pdf/1902.02947](http://arxiv.org/pdf/1902.02947)

