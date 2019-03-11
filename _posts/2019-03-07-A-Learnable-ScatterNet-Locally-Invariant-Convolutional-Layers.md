---
layout: post
title: "A Learnable ScatterNet: Locally Invariant Convolutional Layers"
date: 2019-03-07 19:30:19
categories: arXiv_CV
tags: arXiv_CV CNN
author: Fergal Cotter, Nick Kingsbury
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we explore tying together the ideas from Scattering Transforms and Convolutional Neural Networks (CNN) for Image Analysis by proposing a learnable ScatterNet. Previous attempts at tying them together in hybrid networks have tended to keep the two parts separate, with the ScatterNet forming a fixed front end and a CNN forming a learned backend. We instead look at adding learning between scattering orders, as well as adding learned layers before the ScatterNet. We do this by breaking down the scattering orders into single convolutional-like layers we call 'locally invariant' layers, and adding a learned mixing term to this layer. Our experiments show that these locally invariant layers can improve accuracy when added to either a CNN or a ScatterNet. We also discover some surprising results in that the ScatterNet may be best positioned after one or more layers of learning rather than at the front of a neural network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03137](http://arxiv.org/abs/1903.03137)

##### PDF
[http://arxiv.org/pdf/1903.03137](http://arxiv.org/pdf/1903.03137)

