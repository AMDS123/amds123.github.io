---
layout: post
title: "Learning Densities in Feature Space for Reliable Segmentation of Indoor Scenes"
date: 2019-08-01 15:03:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning
author: Nicolas Marchal, Charlotte Moraldo, Roland Siegwart, Hermann Blum, Cesar Cadena, Abel Gawel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has enabled remarkable advances in semantic segmentation and scene understanding. Yet, introducing novel elements, called out-of-distribution (OoD) data, decreases the performance of existing methods, which are usually limited to a fixed set of classes. This is a problem as autonomous agents will inevitably come across a wide range of objects, all of which cannot be included during training. We propose a novel method to distinguish any object (foreground) from empty building structure (background) in indoor environments. We use normalizing flow to estimate the probability distribution of high-dimensional background descriptors. Foreground objects are therefore detected as areas in an image for which the descriptors are unlikely given the background distribution. As our method does not explicitly learn the representation of individual objects, its performance generalizes well outside of the training examples. Our model results in an innovative solution to reliably segment foreground from background in indoor scenes, which opens the way to a safer deployment of robots in human environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00448](http://arxiv.org/abs/1908.00448)

##### PDF
[http://arxiv.org/pdf/1908.00448](http://arxiv.org/pdf/1908.00448)

