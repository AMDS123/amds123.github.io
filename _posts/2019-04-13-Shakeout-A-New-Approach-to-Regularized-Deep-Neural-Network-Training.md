---
layout: post
title: "Shakeout: A New Approach to Regularized Deep Neural Network Training"
date: 2019-04-13 21:38:16
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Classification
author: Guoliang Kang, Jun Li, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have witnessed the success of deep neural networks in dealing with a plenty of practical problems. Dropout has played an essential role in many successful deep neural networks, by inducing regularization in the model training. In this paper, we present a new regularized training approach: Shakeout. Instead of randomly discarding units as Dropout does at the training stage, Shakeout randomly chooses to enhance or reverse each unit's contribution to the next layer. This minor modification of Dropout has the statistical trait: the regularizer induced by Shakeout adaptively combines $L_0$, $L_1$ and $L_2$ regularization terms. Our classification experiments with representative deep architectures on image datasets MNIST, CIFAR-10 and ImageNet show that Shakeout deals with over-fitting effectively and outperforms Dropout. We empirically demonstrate that Shakeout leads to sparser weights under both unsupervised and supervised settings. Shakeout also leads to the grouping effect of the input units in a layer. Considering the weights in reflecting the importance of connections, Shakeout is superior to Dropout, which is valuable for the deep model compression. Moreover, we demonstrate that Shakeout can effectively reduce the instability of the training process of the deep architecture.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06593](http://arxiv.org/abs/1904.06593)

##### PDF
[http://arxiv.org/pdf/1904.06593](http://arxiv.org/pdf/1904.06593)

