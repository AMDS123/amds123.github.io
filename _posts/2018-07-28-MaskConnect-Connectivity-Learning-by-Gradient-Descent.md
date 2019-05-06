---
layout: post
title: "MaskConnect: Connectivity Learning by Gradient Descent"
date: 2018-07-28 00:41:53
categories: arXiv_CV
tags: arXiv_CV NAS Image_Classification Classification Gradient_Descent
author: Karim Ahmed, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep networks have recently emerged as the model of choice for many computer vision problems, in order to yield good results they often require time-consuming architecture search. To combat the complexity of design choices, prior work has adopted the principle of modularized design which consists in defining the network in terms of a composition of topologically identical or similar building blocks (a.k.a. modules). This reduces architecture search to the problem of determining the number of modules to compose and how to connect such modules. Again, for reasons of design complexity and training cost, previous approaches have relied on simple rules of connectivity, e.g., connecting each module to only the immediately preceding module or perhaps to all of the previous ones. Such simple connectivity rules are unlikely to yield the optimal architecture for the given problem. In this work we remove these predefined choices and propose an algorithm to learn the connections between modules in the network. Instead of being chosen a priori by the human designer, the connectivity is learned simultaneously with the weights of the network by optimizing the loss function of the end task using a modified version of gradient descent. We demonstrate our connectivity learning method on the problem of multi-class image classification using two popular architectures: ResNet and ResNeXt. Experiments on four different datasets show that connectivity learning using our approach yields consistently higher accuracy compared to relying on traditional predefined rules of connectivity. Furthermore, in certain settings it leads to significant savings in number of parameters.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.11473](https://arxiv.org/abs/1807.11473)

##### PDF
[https://arxiv.org/pdf/1807.11473](https://arxiv.org/pdf/1807.11473)

