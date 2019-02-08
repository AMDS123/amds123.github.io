---
layout: post
title: "Deep Learning using Rectified Linear Units"
date: 2019-02-07 06:13:13
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Prediction
author: Abien Fred Agarap
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the use of rectified linear units (ReLU) as the classification function in a deep neural network (DNN). Conventionally, ReLU is used as an activation function in DNNs, with Softmax function as their classification function. However, there have been several studies on using a classification function other than Softmax, and this study is an addition to those. We accomplish this by taking the activation of the penultimate layer $h_{n - 1}$ in a neural network, then multiply it by weight parameters $\theta$ to get the raw scores $o_{i}$. Afterwards, we threshold the raw scores $o_{i}$ by $0$, i.e. $f(o) = \max(0, o_{i})$, where $f(o)$ is the ReLU function. We provide class predictions $\hat{y}$ through argmax function, i.e. argmax $f(x)$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.08375](http://arxiv.org/abs/1803.08375)

##### PDF
[http://arxiv.org/pdf/1803.08375](http://arxiv.org/pdf/1803.08375)

