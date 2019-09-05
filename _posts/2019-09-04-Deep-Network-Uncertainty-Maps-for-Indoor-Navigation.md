---
layout: post
title: "Deep Network Uncertainty Maps for Indoor Navigation"
date: 2019-09-04 10:53:16
categories: arXiv_RO
tags: arXiv_RO Face CNN
author: Francesco Verdoja, Jens Lundell, Ville Kyrki
mathjax: true
---

* content
{:toc}

##### Abstract
Most mobile robots for indoor use rely on 2D laser scanners for localization, mapping and navigation. These sensors, however, cannot detect transparent surfaces or measure the full occupancy of complex objects such as tables. Deep Neural Networks have recently been proposed to overcome this limitation by learning to estimate object occupancy. These estimates are nevertheless subject to uncertainty, making the evaluation of their confidence an important issue for these measures to be useful for autonomous navigation and mapping. In this work we approach the problem from two sides. First we discuss uncertainty estimation in deep models, proposing a solution based on a fully convolutional neural network. The proposed architecture is not restricted by the assumption that the uncertainty follows a Gaussian model, as in the case of many popular solutions for deep model uncertainty estimation, such as Monte-Carlo Dropout. We present results showing that uncertainty over obstacle distances is actually better modeled with a Laplace distribution. Then, we propose a novel approach to build maps based on Deep Neural Network uncertainty models. In particular, we present an algorithm to build a map that includes information over obstacle distance estimates while taking into account the level of uncertainty in each estimate. We show how the constructed map can be used to increase global navigation safety by planning trajectories which avoid areas of high uncertainty, enabling higher autonomy for mobile robots in indoor settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.04891](http://arxiv.org/abs/1809.04891)

##### PDF
[http://arxiv.org/pdf/1809.04891](http://arxiv.org/pdf/1809.04891)

