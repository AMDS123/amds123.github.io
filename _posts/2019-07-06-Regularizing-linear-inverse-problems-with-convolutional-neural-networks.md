---
layout: post
title: "Regularizing linear inverse problems with convolutional neural networks"
date: 2019-07-06 09:30:51
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Reinhard Heckel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks trained on large datsets have emerged as an intriguing alternative for compressing images and solving inverse problems such as denoising and compressive sensing. However, it has only recently been realized that even without training, convolutional networks can function as concise image models, and thus regularize inverse problems. In this paper, we provide further evidence for this finding by studying variations of convolutional neural networks that map few weight parameters to an image. The networks we consider only consist of convolutional operations, with either fixed or parameterized filters followed by ReLU non-linearities. We demonstrate that with both fixed and parameterized convolutional filters those networks enable representing images with few coefficients. What is more, the underparameterization enables regularization of inverse problems, in particular recovering an image from few observations. We show that, similar to standard compressive sensing guarantees, on the order of the number of model parameters many measurements suffice for recovering an image from compressive measurements. Finally, we demonstrate that signal recovery with a un-trained convolutional network outperforms standard l1 and total variation minimization for magnetic resonance imaging (MRI).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03100](http://arxiv.org/abs/1907.03100)

##### PDF
[http://arxiv.org/pdf/1907.03100](http://arxiv.org/pdf/1907.03100)

