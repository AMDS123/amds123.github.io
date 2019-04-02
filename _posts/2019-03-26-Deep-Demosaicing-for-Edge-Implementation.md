---
layout: post
title: "Deep Demosaicing for Edge Implementation"
date: 2019-03-26 15:04:17
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Ramchalam Kinattinkara Ramakrishnan, Jui Shangling, Vahid Patrovi Nia
mathjax: true
---

* content
{:toc}

##### Abstract
Most digital cameras use sensors coated with a Color Filter Array (CFA) to capture channel components at every pixel location, resulting in a mosaic image that does not contain pixel values in all channels. Current research on reconstructing these missing channels, also known as demosaicing, introduces many artifacts, such as zipper effect and false color. Many deep learning demosaicing techniques outperform other classical techniques in reducing the impact of artifacts. However, most of these models tend to be over-parametrized. Consequently, edge implementation of the state-of-the-art deep learning-based demosaicing algorithms on low-end edge devices is a major challenge. We provide an exhaustive search of deep neural network architectures and obtain a pareto front of Color Peak Signal to Noise Ratio (CPSNR) as the performance criterion versus the number of parameters as the model complexity that beats the state-of-the-art. Architectures on the pareto front can then be used to choose the best architecture for a variety of resource constraints. Simple architecture search methods such as exhaustive search and grid search require some conditions of the loss function to converge to the optimum. We clarify these conditions in a brief theoretical study.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00775](http://arxiv.org/abs/1904.00775)

##### PDF
[http://arxiv.org/pdf/1904.00775](http://arxiv.org/pdf/1904.00775)

