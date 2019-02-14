---
layout: post
title: "Why are Saliency Maps Noisy? Cause of and Solution to Noisy Saliency Maps"
date: 2019-02-13 13:25:39
categories: arXiv_CV
tags: arXiv_CV Salient
author: Beomsu Kim, Junghoon Seo, SeungHyun Jeon, Jamyoung Koo, Jeongyeol Choe, Taegyun Jeon
mathjax: true
---

* content
{:toc}

##### Abstract
Saliency Map, the gradient of the score function with respect to the input, is the most basic technique for interpreting deep neural network decisions. However, saliency maps are often visually noisy. Although several hypotheses were proposed to account for this phenomenon, there are few works that provide rigorous analyses of noisy saliency maps. In this paper, we identify that noise occurs in saliency maps when irrelevant features pass through ReLU activation functions. Then we propose Rectified Gradient, a method that solves this problem through layer-wise thresholding during backpropagation. Experiments with neural networks trained on CIFAR-10 and ImageNet showed effectiveness of our method and its superiority to other attribution methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04893](http://arxiv.org/abs/1902.04893)

##### PDF
[http://arxiv.org/pdf/1902.04893](http://arxiv.org/pdf/1902.04893)

