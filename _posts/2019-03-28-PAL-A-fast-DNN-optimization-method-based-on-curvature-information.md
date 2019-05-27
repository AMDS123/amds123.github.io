---
layout: post
title: "PAL: A fast DNN optimization method based on curvature information"
date: 2019-03-28 14:13:21
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Maximus Mutschler, Andreas Zell
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel optimizer for deep neural networks that combines the ideas of Netwon's method and line search to efficiently compute and utilize curvature information. Our work is based on empirical observation suggesting that the loss function can be approximated by a parabola in negative gradient direction. Due to this approximation, we are able to perform a variable and loss function dependent parameter update by jumping directly into the minimum of the approximated parabola. To evaluate our optimizer, we performed multiple comprehensive hyperparameter grid searches for which we trained more than 20000 networks in total. We can show that PAL outperforms RMSPROP, and can outperform gradient descent with momentum and ADAM on large-scale high-dimensional machine learning problems. Furthermore, PAL requires up to 52.2% less training epochs. PyTorch and TensorFlow implementations are provided at https://github.com/cogsys-tuebingen/PAL.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11991](http://arxiv.org/abs/1903.11991)

##### PDF
[http://arxiv.org/pdf/1903.11991](http://arxiv.org/pdf/1903.11991)

