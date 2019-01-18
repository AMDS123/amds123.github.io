---
layout: post
title: "MicroExpNet: An Extremely Small and Fast Model For Expression Recognition From Frontal Face Images"
date: 2019-01-17 07:38:19
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Recognition
author: &#x130;lke &#xc7;u&#x11f;u, Eren &#x15e;ener, Emre Akba&#x15f;
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is aimed at creating extremely small and fast convolutional neural networks (CNN) for the problem of facial expression recognition (FER) from frontal face images. To this end, we employed the popular knowledge distillation (KD) method and identified two major shortcomings with its use: 1) a fine-grained grid search is needed for tuning the temperature hyperparameter and 2) to find the optimal size-accuracy balance, one needs to search for the final network size (i.e. the compression rate). On the other hand, KD is proved to be useful for model compression for the FER problem, and we discovered that its effects gets more and more significant with the decreasing model size. In addition, during the search for a network architecture, we hypothesized that translation invariance achieved using max-pooling layers would not be useful for the FER problem as the expressions are sensitive to small, pixel-wise changes around the eye and the mouth. However, we have found an intriguing improvement on generalization when max-pooling is used. Experiments are made on two widely-used FER datasets, CK+ and Oulu-CASIA. Our smallest model (MicroExpNet), obtained using knowledge distillation, is less than 1MB in size and works at 1851 frames per second on an Intel i7 CPU. Despite being less accurate than the state-of-the-art, MicroExpNet still provides significant insights on the creation of a micro architecture for the FER problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.07011](http://arxiv.org/abs/1711.07011)

##### PDF
[http://arxiv.org/pdf/1711.07011](http://arxiv.org/pdf/1711.07011)

